---
layout: publication
title: 'Search-r1: Training Llms To Reason And Leverage Search Engines With Reinforcement Learning'
authors: Bowen Jin, Hansi Zeng, Zhenrui Yue, Jinsung Yoon, Sercan Arik, Dong Wang, Hamed Zamani, Jiawei Han
conference: "Arxiv"
year: 2025
bibkey: jin2025search
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.09516'}
  - {name: "Code", url: 'https://github.com/PeterGriffinJin/Search-R1'}
tags: ['Masked Language Model', 'Agentic', 'Language Modeling', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Applications', 'Prompting', 'Reinforcement Learning']
---
Efficiently acquiring external knowledge and up-to-date information is
essential for effective reasoning and text generation in large language models
(LLMs). Prompting advanced LLMs with reasoning capabilities to use search
engines during inference is often suboptimal, as the LLM might not fully
possess the capability on how to interact optimally with the search engine.
This paper introduces Search-R1, an extension of reinforcement learning (RL)
for reasoning frameworks where the LLM learns to autonomously generate
(multiple) search queries during step-by-step reasoning with real-time
retrieval. Search-R1 optimizes LLM reasoning trajectories with multi-turn
search interactions, leveraging retrieved token masking for stable RL training
and a simple outcome-based reward function. Experiments on seven
question-answering datasets show that Search-R1 improves performance by 41%
(Qwen2.5-7B) and 20% (Qwen2.5-3B) over various RAG baselines under the same
setting. This paper further provides empirical insights into RL optimization
methods, LLM choices, and response length dynamics in retrieval-augmented
reasoning. The code and model checkpoints are available at
https://github.com/PeterGriffinJin/Search-R1.
