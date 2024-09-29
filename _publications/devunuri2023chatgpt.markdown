---
layout: publication
title: Chatgpt For GTFS\: Benchmarking Llms On GTFS Understanding And Retrieval
authors: Devunuri Saipraneeth, Qiam Shirin, Lehe Lewis
conference: "Arxiv"
year: 2023
bibkey: devunuri2023chatgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.02618"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Tools']
---
The General Transit Feed Specification (GTFS) standard for publishing transit data is ubiquitous. GTFS being tabular data with information spread across different files necessitates specialized tools or packages to retrieve information. Concurrently the use of Large Language Models(LLMs) for text and information retrieval is growing. The idea of this research is to see if the current widely adopted LLMs (ChatGPT) are able to understand GTFS and retrieve information from GTFS using natural language instructions without explicitly providing information. In this research we benchmark OpenAIs GPT-3.5-Turbo and GPT-4 LLMs which are the backbone of ChatGPT. ChatGPT demonstrates a reasonable understanding of GTFS by answering 59.737; (GPT-3.5-Turbo) and 73.337; (GPT-4) of our multiple-choice questions (MCQ) correctly. Furthermore we evaluated the LLMs on information extraction tasks using a filtered GTFS feed containing four routes. We found that program synthesis techniques outperformed zero-shot approaches achieving up to 9337; (9037;) accuracy for simple queries and 6137; (4137;) for complex ones using GPT-4 (GPT-3.5-Turbo).
