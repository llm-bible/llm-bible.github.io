---
layout: publication
title: Chatcot Tool45;augmented Chain45;of45;thought Reasoning On Chat45;based Large Language Models
authors: Chen Zhipeng, Zhou Kun, Zhang Beichen, Gong Zheng, Zhao Wayne Xin, Wen Ji-rong
conference: "Arxiv"
year: 2023
bibkey: chen2023tool
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14323"}
  - {name: "Code", url: "https://github.com/RUCAIBOX/ChatCoT&#125;"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Although large language models (LLMs) have achieved excellent performance in a variety of evaluation benchmarks they still struggle in complex reasoning tasks which require specific knowledge and multi45;hop reasoning. To improve the reasoning abilities we propose ChatCoT a tool45;augmented chain45;of45;thought reasoning framework for chat45;based LLMs (e.g. ChatGPT). In ChatCoT we model the chain45;of45;thought (CoT) reasoning as multi45;turn conversations to utilize tools in a more natural way through chatting. At each turn LLMs can either interact with tools or perform the reasoning. Our approach can effectively leverage the multi45;turn conversation ability of chat45;based LLMs and integrate the thought chain following and tools manipulation in a unified way. Specially we initialize the early turns of the conversation by the knowledge about tools tasks and reasoning format and propose an iterative tool45;augmented reasoning step to perform step45;by45;step tool45;augmented reasoning. The experiment results on two complex reasoning datasets (MATH and HotpotQA) have shown the effectiveness of ChatCoT on complex reasoning tasks achieving a 7.937; relative improvement over the state45;of45;the45;art baseline. Our code and data are available at url123;https://github.com/RUCAIBOX/ChatCoT&#125;.
