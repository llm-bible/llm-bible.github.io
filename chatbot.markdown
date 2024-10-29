---
layout: page
title: Chat with the LLM-Bible Bot
description: LLM-Bible Chatbot
---
The LLM-Bible Chatbot can help you find relevant papers, with 10,000 papers currently ingested into the vector index. Some example queries:

- *"What are the latest advancements in transformer models?"*
- *"Can you explain how fine-tuning works in LLMs?"*
- *"Which papers explore LLMs for multimodal tasks?"*
- *"What is retrieval-augmented generation (RAG), and which papers discuss it?"*

<div class="container">
    <h2>Popular Queries</h2>
    <ul id="popular-queries-list"></ul>
</div>

Feel free to ask any of your own questions!

<div class="chat-container">
  <div class="chatbox">
    <div id="messages" class="messages"></div>
    <div class="input-area">
      <input id="query" type="text" placeholder="Ask a question..." class="chat-input">
      <button onclick="sendQuery()" class="send-button">Send</button>
    </div>
  </div>
</div>

<style>
/* Chatbox Container */
.chat-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 50px;
}

.chatbox {
  width: 90%; /* Makes it take up 80% of the screen width */
  max-width: 900px; /* The maximum width for larger screens */
  min-width: 400px; /* The minimum width for smaller screens */
  border-radius: 10px;
  overflow: hidden;
  background-color: #ffffff;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: column;
}

.messages {
  padding: 15px;
  height: 400px;
  overflow-y: scroll;
  border-bottom: 1px solid #e0e0e0;
}

.message {
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 10px;
  max-width: 80%;
  word-wrap: break-word;
}

.user {
  align-self: flex-end;
  background-color: #d1e7ff;
  text-align: right;
}

.bot {
  align-self: flex-start;
  background-color: #e8f5e9;
  text-align: left;
}

/* Adjust the input area */
.input-area {
  display: flex;
  padding: 10px;
  border-top: 1px solid #e0e0e0;
  background-color: #fafafa;
}

.chat-input {
  flex-grow: 1;
  padding: 15px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px;
  outline: none;
  width: 100%; /* Make the input box wider */
}

.send-button {
  margin-left: 10px;
  padding: 15px 25px;
  background-color: #2196f3;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.send-button:hover {
  background-color: #1e88e5;
}
</style>

<script>
// Fetch popular queries from your Flask endpoint
fetch("https://aicoinanalysis.com/popular-queries")
    .then(response => response.json())
    .then(data => {
        const queriesList = document.getElementById("popular-queries-list");

        if (data.length === 0) {
            // Display default message if no queries are returned
            const defaultMessage = document.createElement("li");
            defaultMessage.textContent = "No queries yet";
            queriesList.appendChild(defaultMessage);
        } else {
            // Display each popular query
            data.forEach(item => {
                const listItem = document.createElement("li");
                listItem.innerHTML = `<strong>${capitalizeFirstLetter(item.query)}</strong>`;
                queriesList.appendChild(listItem);
            });
        }
    })
    .catch(error => {
        console.error("Error loading popular queries:", error);
    });

// Function to capitalize the first letter of each query
function capitalizeFirstLetter(query) {
    return query.charAt(0).toUpperCase() + query.slice(1);
}
</script>

<script>
window.onload = function() {
  displayWelcomeMessage();
};

async function sendQuery() {
  const query = document.getElementById("query").value;
  const messagesDiv = document.getElementById("messages");

  console.log("User query:", query);  // Log the user's query

  // Display user message
  appendMessage("user", "You: " + query);
  document.getElementById("query").value = ""; // Clear input

  try {
    console.log("Sending request to the backend...");

    // Fetch response from backend
    const response = await fetch("https://aicoinanalysis.com/chat", {
      method: "POST",
      headers: {
        "Content-Type": "application/json"
      },
      body: JSON.stringify({ user_input: query })
    });

    if (response.status === 429) {
      displayBotMessage("Rate limit reached, please try again tomorrow.");
      console.warn("Rate limit reached.");
      return;
    }

    if (!response.ok) {
      const errorData = await response.json();
      throw new Error(errorData.error || "Unknown error occurred");
    }

    const result = await response.json();
    console.log("Parsed response JSON:", result);

    if (result.answer) {
      parseAndDisplayAnswer(result.answer);
    } else {
      displayBotMessage("No answer field found in the response.");
      console.warn("No 'answer' field found in the response.");
    }
  } catch (error) {
    displayBotMessage(`Error - ${error.message}`);
    console.error("Error occurred:", error);
  }

  messagesDiv.scrollTop = messagesDiv.scrollHeight;
  console.log("Scrolled to bottom.");
}

// Function to display a welcome message when the page loads
function displayWelcomeMessage() {
  displayBotMessage("Hello! I'm LLM-Bible Bot. How can I assist you today?");
}

// Function to parse JSON content within 'answer' and display it
function parseAndDisplayAnswer(answer) {
  try {
    const jsonStart = answer.indexOf("[");
    const jsonEnd = answer.lastIndexOf("]") + 1;

    if (jsonStart === -1 || jsonEnd === -1) {
      throw new Error("No valid JSON block found.");
    }

    const jsonString = answer.substring(jsonStart, jsonEnd);
    const papers = JSON.parse(jsonString);
    console.log("Parsed papers:", papers);

    const botMessage = document.createElement("div");
    botMessage.classList.add("message", "bot");
    botMessage.innerHTML = `<p>LLM-Bible Bot:</p><ul>${formatBotResponse(papers)}</ul>`;
    document.getElementById("messages").appendChild(botMessage);
  } catch (jsonError) {
    console.error("Error parsing JSON in 'answer' field:", jsonError);
    displayBotMessage("Error parsing the response data.");
  }
}

// Helper function to display bot messages
function displayBotMessage(text) {
  const errorMessage = document.createElement("div");
  errorMessage.classList.add("message", "bot");
  errorMessage.textContent = `LLM-Bible Bot: ${text}`;
  document.getElementById("messages").appendChild(errorMessage);
}

// Helper function to append user messages
function appendMessage(className, text) {
  const message = document.createElement("div");
  message.classList.add("message", className);
  message.textContent = text;
  document.getElementById("messages").appendChild(message);
}

// Function to format bot response into HTML bullet points with proper capitalization
function formatBotResponse(papers) {
  if (!Array.isArray(papers)) {
    console.warn("Response JSON is not an array:", papers);
    return "<li>No papers found.</li>";
  }

  return papers.map(paper => `
    <li><strong><a href="${paper.url}" target="_blank">${capitalizeTitle(paper.name)}</a></strong>: ${capitalizeSentence(paper.description)}</li>
  `).join('');
}

// Helper function to capitalize the first letter of each significant word in the title
function capitalizeTitle(title) {
  const minorWords = ["the", "in", "and", "of", "to", "for"];
  return title.split(" ").map((word, index) => {
    // Capitalize first word and significant words; keep minor words lowercase unless first
    if (minorWords.includes(word.toLowerCase()) && index !== 0) {
      return word.toLowerCase();
    }
    return word.charAt(0).toUpperCase() + word.slice(1).toLowerCase();
  }).join(" ");
}

// Helper function to capitalize the first letter of a sentence
function capitalizeSentence(sentence) {
  return sentence.charAt(0).toUpperCase() + sentence.slice(1);
}
</script>
