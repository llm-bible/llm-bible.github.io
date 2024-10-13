---
layout: default
title: A Comprehensive Overview of Large Language Models (LLMs) with Papers, Resources and Colab Notebooks
---

### Welcome to the LLM Bible!

Large Language Models (LLMs) represent a groundbreaking leap in artificial intelligence, enabling machines to interpret, generate, and engage with human language in ways that are both profound and transformative. These models, trained on diverse datasets containing trillions of words, have become the backbone of numerous applications that influence how we gather information, make decisions, and interact with technology.

![Emergent capabilities of LLMs with growing parameter count](llm-tree.gif)

This website is dedicated to exploring the fascinating world of LLMs. Here, you will find a curated collection of research papers, Colab Notebooks, and educational materials to learn about LLMs. 

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
you explore, [search and navigate]({% link papers.html %}) the literature in this area.

### Contributing

This research area is evolving so fast that a static review cannot keep up.
But a website can! We hope to make this site a living document.
Anyone can add a paper to this web site, by completing a [web form](contributing.html).

---

## Chat with the LLM Bible Bot

Feel free to ask any questions related to Large Language Models (LLMs) or research resources here:

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
  width: 400px;
  max-width: 100%;
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

.input-area {
  display: flex;
  padding: 10px;
  border-top: 1px solid #e0e0e0;
  background-color: #fafafa;
}

.chat-input {
  flex-grow: 1;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px;
  outline: none;
}

.send-button {
  margin-left: 10px;
  padding: 10px 20px;
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
async function sendQuery() {
  const query = document.getElementById("query").value;
  const messagesDiv = document.getElementById("messages");

  // Display user message
  const userMessage = document.createElement("div");
  userMessage.classList.add("message", "user");
  userMessage.textContent = "You: " + query;
  messagesDiv.appendChild(userMessage);
  document.getElementById("query").value = ""; // Clear input

  // Fetch response from backend (Replace URL with your API endpoint)
  const response = await fetch("https://your-backend-url.com/query", {
    method: "POST",
    headers: {
      "Content-Type": "application/json"
    },
    body: JSON.stringify({ query })
  });

  const result = await response.json();

  // Display bot response
  const botMessage = document.createElement("div");
  botMessage.classList.add("message", "bot");
  botMessage.textContent = "Bot: " + result.answer; // Customize based on API response
  messagesDiv.appendChild(botMessage);

  // Scroll to the bottom of the chat
  messagesDiv.scrollTop = messagesDiv.scrollHeight;
}
</script>

---

Copyright © Sean Moran 2024. All opinions are my own.
