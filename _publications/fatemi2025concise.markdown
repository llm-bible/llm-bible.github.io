---
layout: publication
title: 'Concise Reasoning Via Reinforcement Learning'
authors: Mehdi Fatemi, Banafsheh Rafiee, Mingjie Tang, Kartik Talamadupula
conference: "Arxiv"
year: 2025
bibkey: fatemi2025concise
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.05185'}
tags: ['Reinforcement Learning', 'Agentic', 'Efficiency and Optimization', 'Training Techniques']
---
Despite significant advancements in large language models (LLMs), a major drawback of reasoning models is their enormous token usage, which increases computational cost, resource requirements, and response time. In this work, we revisit the core principles of reinforcement learning (RL) and, through mathematical analysis, demonstrate that the tendency to generate lengthy responses arises inherently from RL-based optimization during training. This finding questions the prevailing assumption that longer responses inherently improve reasoning accuracy. Instead, we uncover a natural correlation between conciseness and accuracy that has been largely overlooked. We show that introducing a secondary phase of RL training, using a very small set of problems, can significantly reduce chains of thought while maintaining or even enhancing accuracy. Additionally, we demonstrate that, while GRPO shares some interesting properties of PPO, it suffers from collapse modes, which limit its reliability for concise reasoning. Finally, we validate our conclusions through extensive experimental results.
