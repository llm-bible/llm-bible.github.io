---
layout: default
title: A Comprehensive Overview of Large Language Models (LLMs) with Papers, Resources and Colab Notebooks
---

### Welcome to the LLM Bible!

Large Language Models (LLMs) represent a groundbreaking leap in artificial intelligence, enabling machines to interpret, generate, and engage with human language in ways that are both profound and transformative. These models, trained on diverse datasets containing trillions of words, have become the backbone of numerous applications that influence how we gather information, make decisions, and interact with technology.

![Emergent capabilities of LLMs with growing parameter count](llm-tree.gif)

This website is dedicated to exploring the fascinating world of LLMs. Here, you will find a curated collection of research papers and educational materials to learn about LLMs. 

#### 🏷 Chat with 10,000 LLM Papers

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

// Function to format bot response into HTML bullet points
function formatBotResponse(papers) {
  if (!Array.isArray(papers)) {
    console.warn("Response JSON is not an array:", papers);
    return "<li>No papers found.</li>";
  }

  return papers.map(paper => `
    <li><strong><a href="${paper.url}" target="_blank">${paper.name}</a></strong>: ${paper.description}</li>
  `).join('');
}
</script>

#### 🏷 Browse Papers by Tag
{% assign rawtags = Array.new %}
{% for publication in site.publications %}
  {% assign ttags = publication.tags  %}  
  {% assign rawtags = rawtags | concat: ttags %}  
{% endfor %}
{% assign rawtags = rawtags | uniq | sort_natural %}
{% for tag in rawtags %}<tag><a href="/tags.html#{{ tag }}">{{ tag }}</a></tag> {% endfor %}

### About This Site

This site is an experiment: a [living literature review](https://en.wikipedia.org/wiki/Living_review) that allows
you to explore, [search and navigate]({% link papers.html %}) the literature in this area.

### Contributing

This research area is evolving so fast that a static review cannot keep up.
But a website can! We hope to make this site a living document.
Anyone can add a paper to this website by completing a [web form](contributing.html).

---

Copyright © [Sean Moran](https://sjmoran.github.io/) 2024. All opinions are my own.
