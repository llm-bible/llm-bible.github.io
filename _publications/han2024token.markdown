---
layout: publication
title: 'Token-budget-aware LLM Reasoning'
authors: Tingxu Han, Zhenting Wang, Chunrong Fang, Shiyu Zhao, Shiqing Ma, Zhenyu Chen
conference: "Arxiv"
year: 2024
bibkey: han2024token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.18547'}
  - {name: "Code", url: 'https://github.com/GeniusHTX/TALE'}
tags: ['Prompting', 'Has Code', 'Efficiency and Optimization', 'Tools']
---
Reasoning is critical for large language models (LLMs) to excel in a wide range of tasks. While methods like Chain-of-Thought (CoT) reasoning and enhance LLM performance by decomposing problems into intermediate steps, they also incur significant overhead in token usage, leading to increased costs. We find that the reasoning process of current LLMs is unnecessarily lengthy and it can be compressed by including a reasonable token budget in the prompt, but the choice of token budget plays a crucial role in the actual compression effectiveness. We then propose a token-budget-aware LLM reasoning framework that dynamically adjusts the number of reasoning tokens based on the reasoning complexity of each problem. Experiments show that our method effectively reduces token costs in CoT reasoning with only a slight performance reduction, offering a practical solution to balance efficiency and accuracy in LLM reasoning. Code: https://github.com/GeniusHTX/TALE
