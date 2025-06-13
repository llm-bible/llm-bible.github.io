---
layout: publication
title: 'Incorporating External Knowledge And Goal Guidance For Llm-based Conversational Recommender Systems'
authors: Chuang Li, Yang Deng, Hengchang Hu, Min-yen Kan, Haizhou Li
conference: "Arxiv"
year: 2024
bibkey: li2024incorporating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.01868'}
tags: ['Agentic', 'RAG', 'GPT', 'Model Architecture', 'Tools', 'RecSys']
---
This paper aims to efficiently enable large language models (LLMs) to use
external knowledge and goal guidance in conversational recommender system (CRS)
tasks. Advanced LLMs (e.g., ChatGPT) are limited in domain-specific CRS tasks
for 1) generating grounded responses with recommendation-oriented knowledge, or
2) proactively leading the conversations through different dialogue goals. In
this work, we first analyze those limitations through a comprehensive
evaluation, showing the necessity of external knowledge and goal guidance which
contribute significantly to the recommendation accuracy and language quality.
In light of this finding, we propose a novel ChatCRS framework to decompose the
complex CRS task into several sub-tasks through the implementation of 1) a
knowledge retrieval agent using a tool-augmented approach to reason over
external Knowledge Bases and 2) a goal-planning agent for dialogue goal
prediction. Experimental results on two multi-goal CRS datasets reveal that
ChatCRS sets new state-of-the-art benchmarks, improving language quality of
informativeness by 17% and proactivity by 27%, and achieving a tenfold
enhancement in recommendation accuracy.
