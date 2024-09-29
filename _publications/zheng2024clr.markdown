---
layout: publication
title: "Clr-fact: Evaluating The Complex Logical Reasoning Capability Of Large Language Models Over Factual Knowledge"
authors: Zheng Tianshi, Bai Jiaxin, Wang Yicheng, Fang Tianqing, Guo Yue, Yim Yauwai, Song Yangqiu
conference: "Arxiv"
year: 2024
bibkey: zheng2024clr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20564"}
tags: ['Applications', 'In Context Learning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
While large language models (LLMs) have demonstrated impressive capabilities across various natural language processing tasks by acquiring rich factual knowledge from their broad training data their ability to synthesize and logically reason with this knowledge in complex ways remains underexplored. In this work we present a systematic evaluation of state-of-the-art LLMs complex logical reasoning abilities through a novel benchmark of automatically generated complex reasoning questions over general domain and biomedical knowledge graphs. Our extensive experiments employing diverse in-context learning techniques reveal that LLMs excel at reasoning over general world knowledge but face significant challenges with specialized domain-specific knowledge. We find that prompting with explicit Chain-of-Thought demonstrations can substantially improve LLM performance on complex logical reasoning tasks with diverse logical operations. Interestingly our controlled evaluations uncover an asymmetry where LLMs display proficiency at set union operations but struggle considerably with set intersections - a key building block of logical reasoning. To foster further work we will publicly release our evaluation benchmark and code.
