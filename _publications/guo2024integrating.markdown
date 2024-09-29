---
layout: publication
title: Integrating Large Language Models With Graphical Session-based Recommendation
authors: Guo Naicheng, Cheng Hongwei, Liang Qianqiao, Chen Linxun, Han Bing
conference: "Arxiv"
year: 2024
bibkey: guo2024integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16539"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
With the rapid development of Large Language Models (LLMs) various explorations have arisen to utilize LLMs capability of context understanding on recommender systems. While pioneering strategies have primarily transformed traditional recommendation tasks into challenges of natural language generation there has been a relative scarcity of exploration in the domain of session-based recommendation (SBR) due to its specificity. SBR has been primarily dominated by Graph Neural Networks which have achieved many successful outcomes due to their ability to capture both the implicit and explicit relationships between adjacent behaviors. The structural nature of graphs contrasts with the essence of natural language posing a significant adaptation gap for LLMs. In this paper we introduce large language models with graphical Session-Based recommendation named LLMGR an effective framework that bridges the aforementioned gap by harmoniously integrating LLMs with Graph Neural Networks (GNNs) for SBR tasks. This integration seeks to leverage the complementary strengths of LLMs in natural language understanding and GNNs in relational data processing leading to a more powerful session-based recommender system that can understand and recommend items within a session. Moreover to endow the LLM with the capability to empower SBR tasks we design a series of prompts for both auxiliary and major instruction tuning tasks. These prompts are crafted to assist the LLM in understanding graph-structured data and align textual information with nodes effectively translating nuanced user interactions into a format that can be understood and utilized by LLM architectures. Extensive experiments on three real-world datasets demonstrate that LLMGR outperforms several competitive baselines indicating its effectiveness in enhancing SBR tasks and its potential as a research direction for future exploration.
