---
layout: publication
title: 'Multi-layer GRPO: Enhancing Reasoning And Self-correction In Large Language Models'
authors: Fei Ding, Baiqiao Wang, Zijian Zeng, Youwei Wang
conference: "Arxiv"
year: 2025
bibkey: ding2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04746"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
The Group Relative Policy Optimization (GRPO) algorithm has demonstrated considerable success in enhancing the reasoning capabilities of large language models (LLMs), as evidenced by DeepSeek-R1. However, the absence of intermediate supervision in GRPO frequently leads to inefficient exploration dynamics. A single error in a complex reasoning chain can invalidate the entire solution, resulting in abrupt reward vanishing and compromising training stability.To address these challenges, we propose MGRPO (Multi-layer GRPO). MGRPO operates in two layers: the first layer employs standard GRPO to generate an initial response. This response, along with the original query, is then fed into a second-layer GRPO process. This second layer is specifically trained to identify and correct errors in the initial response, effectively creating a self-correction loop. This mechanism provides implicit process-level supervision by rewarding successful error correction, without requiring an explicit, densely-annotated reward model. Experimental results on several mathematical reasoning benchmarks demonstrate that MGRPO significantly outperforms standard GRPO, achieving superior performance by fostering both reasoning and self-correction abilities.
