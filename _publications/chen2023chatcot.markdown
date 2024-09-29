---
layout: publication
title: Chatcot Tool-augmented Chain-of-thought Reasoning On Chat-based Large Language Models
authors: Chen Zhipeng, Zhou Kun, Zhang Beichen, Gong Zheng, Zhao Wayne Xin, Wen Ji-rong
conference: "Arxiv"
year: 2023
bibkey: chen2023chatcot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14323"}
  - {name: "Code", url: "https://github.com/RUCAIBOX/ChatCoT"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Although large language models (LLMs) have achieved excellent performance in a variety of evaluation benchmarks they still struggle in complex reasoning tasks which require specific knowledge and multi-hop reasoning. To improve the reasoning abilities we propose ChatCoT a tool-augmented chain-of-thought reasoning framework for chat-based LLMs (e.g. ChatGPT). In ChatCoT we model the chain-of-thought (CoT) reasoning as multi-turn conversations to utilize tools in a more natural way through chatting. At each turn LLMs can either interact with tools or perform the reasoning. Our approach can effectively leverage the multi-turn conversation ability of chat-based LLMs and integrate the thought chain following and tools manipulation in a unified way. Specially we initialize the early turns of the conversation by the knowledge about tools tasks and reasoning format and propose an iterative tool-augmented reasoning step to perform step-by-step tool-augmented reasoning. The experiment results on two complex reasoning datasets (MATH and HotpotQA) have shown the effectiveness of ChatCoT on complex reasoning tasks achieving a 7.937; relative improvement over the state-of-the-art baseline. Our code and data are available at urlhttps://github.com/RUCAIBOX/ChatCoT}.
