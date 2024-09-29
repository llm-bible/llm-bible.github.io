---
layout: publication
title: Chain Of Preference Optimization Improving Chain45;of45;thought Reasoning In Llms
authors: Zhang Xuan, Du Chao, Pang Tianyu, Liu Qian, Gao Wei, Lin Min
conference: "Arxiv"
year: 2024
bibkey: zhang2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09136"}
  - {name: "Code", url: "https://github.com/sail&#45;sg/CPO"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'RAG', 'Reinforcement Learning']
---
The recent development of chain45;of45;thought (CoT) decoding has enabled large language models (LLMs) to generate explicit logical reasoning paths for complex problem45;solving. However research indicates that these paths are not always deliberate and optimal. The tree45;of45;thought (ToT) method employs tree45;searching to extensively explore the reasoning space and find better reasoning paths that CoT decoding might overlook. This deliberation however comes at the cost of significantly increased inference complexity. In this work we demonstrate that fine45;tuning LLMs leveraging the search tree constructed by ToT allows CoT to achieve similar or better performance thereby avoiding the substantial inference burden. This is achieved through Chain of Preference Optimization (CPO) where LLMs are fine45;tuned to align each step of the CoT reasoning paths with those of ToT using the inherent preference information in the tree45;search process. Extensive experimental results show that CPO significantly improves LLM performance in solving a variety of complex problems including question answering fact verification and arithmetic reasoning demonstrating its effectiveness. Our code is available at https://github.com/sail&#45;sg/CPO.
