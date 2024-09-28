---
layout: publication
title: SirLLM Streaming Infinite Retentive LLM
authors: Yao Yao, Li Zuchao, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: yao2024sirllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12528"}
  - {name: "Code", url: "https://github.com/Zoeyyao27/SirLLM"}
tags: ['Arxiv', 'Has Code', 'LLM', 'A', 'Pretraining Methods']
---
As Large Language Models (LLMs) become increasingly prevalent in various domains their ability to process inputs of any length and maintain a degree of memory becomes essential. However the one-off input of overly long texts is limited as studies have shown that when input lengths exceed the LLMs pre-trained text length there is a dramatic decline in text generation capabilities. Moreover simply extending the length of pre-training texts is impractical due to the difficulty in obtaining long text data and the substantial memory consumption costs this would entail for LLMs. Recent efforts have employed streaming inputs to alleviate the pressure of excessively long text inputs but this approach can significantly impair the models long-term memory capabilities. Motivated by this challenge we introduce Streaming Infinite Retentive LLM (SirLLM) which allows LLMs to maintain longer memory during infinite-length dialogues without the need for fine-tuning. SirLLM utilizes the Token Entropy metric and a memory decay mechanism to filter key phrases endowing LLMs with both long-lasting and flexible memory. We designed three distinct tasks and constructed three datasets to measure the effectiveness of SirLLM from various angles (1) DailyDialog; (2) Grocery Shopping; (3) Rock-Paper-Scissors. Our experimental results robustly demonstrate that SirLLM can achieve stable and significant improvements across different LLMs and tasks compellingly proving its effectiveness. When having a coversation A sir could forget himself but SirLLM never does! Our code is publicly available at https://github.com/Zoeyyao27/SirLLM
