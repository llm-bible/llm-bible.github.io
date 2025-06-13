---
layout: publication
title: 'Arctic-text2sql-r1: Simple Rewards, Strong Reasoning In Text-to-sql'
authors: Zhewei Yao, Guoheng Sun, Lukasz Borchmann, Zheyu Shen, Minghang Deng, Bohan Zhai, Hao Zhang, Ang Li, Yuxiong He
conference: "Arxiv"
year: 2025
bibkey: yao2025arctic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20315"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Applications']
---
Translating natural language into SQL (Test2SQL) is a longstanding challenge at the intersection of natural language understanding and structured data access. While large language models (LLMs) have significantly improved fluency in SQL generation, producing correct and executable SQL--particularly for complex queries--remains a bottleneck. We present Arctic-Text2SQL-R1, a reinforcement learning (RL) framework and model family designed to generate accurate, executable SQL using a lightweight reward signal based solely on execution correctness. Our approach avoids brittle intermediate supervision and complex reward shaping, promoting stable training and alignment with the end task. Combined with carefully curated data, strong supervised initialization, and effective training practices, Arctic-Text2SQL-R1 achieves state-of-the-art execution accuracy across six diverse Test2SQL benchmarks, including the top position on the BIRD leaderboard. Notably, our 7B model outperforms prior 70B-class systems, highlighting the framework's scalability and efficiency. We further demonstrate inference-time robustness through simple extensions like value retrieval and majority voting. Extensive experiments and ablation studies offer both positive and negative insights, providing practical guidance for future Test2SQL research.
