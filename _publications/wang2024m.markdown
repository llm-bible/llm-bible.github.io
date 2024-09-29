---
layout: publication
title: M-RAG&#58; Reinforcing Large Language Model Performance Through Retrieval-augmented Generation With Multiple Partitions
authors: Wang Zheng, Teo Shu Xian, Ouyang Jieer, Xu Yongjun, Shi Wei
conference: "Arxiv"
year: 2024
bibkey: wang2024m
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16420"}
tags: ['Agentic', 'Applications', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by retrieving relevant memories from an external database. However existing RAG methods typically organize all memories in a whole database potentially limiting focus on crucial memories and introducing noise. In this paper we introduce a multiple partition paradigm for RAG (called M-RAG) where each database partition serves as a basic unit for RAG execution. Based on this paradigm we propose a novel framework that leverages LLMs with Multi-Agent Reinforcement Learning to optimize different language generation tasks explicitly. Through comprehensive experiments conducted on seven datasets spanning three language generation tasks and involving three distinct language model architectures we confirm that M-RAG consistently outperforms various baseline methods achieving improvements of 1137; 837; and 1237; for text summarization machine translation and dialogue generation respectively.
