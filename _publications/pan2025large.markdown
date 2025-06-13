---
layout: publication
title: 'Large Language Models Think Too Fast To Explore Effectively'
authors: Lan Pan, Hanbo Xie, Robert C. Wilson
conference: "Arxiv"
year: 2025
bibkey: pan2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18009"}
tags: ['Fine-Tuning', 'Transformer', 'Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
Large Language Models (LLMs) have emerged with many intellectual capacities. While numerous benchmarks assess their intelligence, limited attention has been given to their ability to explore--an essential capacity for discovering new information and adapting to novel environments in both natural and artificial systems. The extent to which LLMs can effectively explore, particularly in open-ended tasks, remains unclear. This study investigates whether LLMs can surpass humans in exploration during an open-ended task, using Little Alchemy 2 as a paradigm, where agents combine elements to discover new ones. Results show most LLMs underperform compared to humans, except for the o1 model, with traditional LLMs relying primarily on uncertainty-driven strategies, unlike humans who balance uncertainty and empowerment. Results indicate that traditional reasoning-focused LLMs, such as GPT-4o, exhibit a significantly faster and less detailed reasoning process, limiting their exploratory performance. In contrast, the DeepSeek reasoning model demonstrates prolonged, iterative thought processes marked by repetitive analysis of combinations and past trials, reflecting a more thorough and human-like exploration strategy. Representational analysis of the models with Sparse Autoencoders (SAE) revealed that uncertainty and choices are represented at earlier transformer blocks, while empowerment values are processed later, causing LLMs to think too fast and make premature decisions, hindering effective exploration. These findings shed light on the limitations of LLM exploration and suggest directions for improving their adaptability.
