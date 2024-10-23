---
layout: page
title: Chat with the LLM-Bible Bot
description: LLM-Bible Chatbot
---
Hello! I am the LLM-Bible bot, your expert guide through the vast collection of over 10,000 papers on Large Language Models (LLMs). You can ask me anything about LLMs, research resources, or key trends in the field. Here are some examples of questions you could ask me:

- *"What are the latest advancements in transformer models?"*
- *"Can you explain how fine-tuning works in LLMs?"*
- *"Which papers explore LLMs for multimodal tasks?"*
- *"What is retrieval-augmented generation (RAG), and which papers discuss it?"*
- *"Tell me about papers focusing on reinforcement learning with LLMs."*
- *"Can you recommend some papers on the use of LLMs in NLP tasks?"*
- *"What are the key conferences for LLM research?"*
- *"How can I use LLMs for code generation?"*
- *"Can you surprise me with very unique LLM papers?"*

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
import openai
import json

def get_formatted_response(question, context, citations_in_text):
    response = openai.ChatCompletion.create(
        model="gpt-3.5-turbo",
        messages=[
            {"role": "system", "content": "You are a helpful assistant who provides concise answers in JSON format."},
            {"role": "user", "content": (
                f"Question: {question}\n\n"
                f"Context: {context}\n\n"
                f"Please return the answer in the following JSON format, where each object contains the exact paper title, its key, and a short description of how it addresses the question. Use the key to construct the URL in the format 'https://llm-bible.github.io/publications/<key>/':\n\n"
                f"[\n"
                f"  {{\n"
                f"    \"name\": \"<Paper Title>\",\n"
                f"    \"key\": \"<key>\",\n"
                f"    \"url\": \"https://llm-bible.github.io/publications/<key>/\",\n"
                f"    \"description\": \"<Short description of how this paper addresses the question.>\"\n"
                f"  }},\n"
                f"  {{\n"
                f"    \"name\": \"<Paper Title>\",\n"
                f"    \"key\": \"<key>\",\n"
                f"    \"url\": \"https://llm-bible.github.io/publications/<key>/\",\n"
                f"    \"description\": \"<Short description of how this paper addresses the question.>\"\n"
                f"  }}\n"
                f"]\n\n"
                f"Here are the relevant papers:\n{citations_in_text}\n\n"
                f"Examples:\n"
                f"[\n"
                f"  {{\n"
                f"    \"name\": \"Mixture-of-loras: An Efficient Multitask Tuning For Large Language Models\",\n"
                f"    \"key\": \"feng2024mixture\",\n"
                f"    \"url\": \"https://llm-bible.github.io/publications/feng2024mixture/\",\n"
                f"    \"description\": \"This paper presents the Mixture-of-LoRAs (MoA) architecture, a novel tuning method for LLMs aimed at multitask learning. It improves performance by mitigating interference between tasks, using domain-specific modules with routing strategies, making it suitable for diverse tasks in instruction tuning.\"\n"
                f"  }},\n"
                f"  {{\n"
                f"    \"name\": \"Llama-vits: Enhancing TTS Synthesis With Semantic Awareness\",\n"
                f"    \"key\": \"feng2024llama\",\n"
                f"    \"url\": \"https://llm-bible.github.io/publications/feng2024llama/\",\n"
                f"    \"description\": \"This paper introduces Llama-VITS, a TTS synthesis method that enriches the semantic content of text using LLMs, particularly Llama2, integrated with the VITS model. It demonstrates improved emotive expressiveness on a curated emotional speech dataset, offering potential enhancements in generating emotionally expressive speech.\"\n"
                f"  }}\n"
                f"]"
            )}
        ]
    )

    # Extract the response content
    response_content = response['choices'][0]['message']['content']

    # Clean any unwanted characters like '↵' (if present)
    clean_response = response_content.replace('↵', '').strip()

    # Optionally, convert the cleaned string into JSON format if needed
    try:
        json_response = json.loads(clean_response)
        return json_response
    except json.JSONDecodeError:
        # If there's an issue decoding, return the raw response
        return clean_response


</script>

