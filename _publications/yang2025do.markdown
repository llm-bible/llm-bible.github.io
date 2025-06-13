---
layout: publication
title: 'Do Not Let Low-probability Tokens Over-dominate In RL For Llms'
authors: Zhihe Yang, Xufang Luo, Zilong Wang, Dongqi Han, Zhiyuan He, Dongsheng Li, Yunjian Xu
conference: "Arxiv"
year: 2025
bibkey: yang2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12929"}
  - {name: "Code", url: "https://github.com/zhyang2226/AR-Lopti"}
tags: ['Agentic', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Reinforcement learning (RL) has become a cornerstone for enhancing the reasoning capabilities of large language models (LLMs), with recent innovations such as Group Relative Policy Optimization (GRPO) demonstrating exceptional effectiveness. In this study, we identify a critical yet underexplored issue in RL training: low-probability tokens disproportionately influence model updates due to their large gradient magnitudes. This dominance hinders the effective learning of high-probability tokens, whose gradients are essential for LLMs' performance but are substantially suppressed. To mitigate this interference, we propose two novel methods: Advantage Reweighting and Low-Probability Token Isolation (Lopti), both of which effectively attenuate gradients from low-probability tokens while emphasizing parameter updates driven by high-probability tokens. Our approaches promote balanced updates across tokens with varying probabilities, thereby enhancing the efficiency of RL training. Experimental results demonstrate that they substantially improve the performance of GRPO-trained LLMs, achieving up to a 46.2% improvement in K&K Logic Puzzle reasoning tasks. Our implementation is available at https://github.com/zhyang2226/AR-Lopti.
