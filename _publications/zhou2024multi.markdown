---
layout: publication
title: Multi-stage Balanced Distillation Addressing Long-tail Challenges In Sequence-level Knowledge Distillation
authors: Zhou Yuhang, Zhu Jing, Xu Paiheng, Liu Xiaoyu, Wang Xiyao, Koutra Danai, Ai Wei, Huang Furong
conference: "Arxiv"
year: 2024
bibkey: zhou2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13114"}
tags: ['Distillation', 'Efficiency And Optimization', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have significantly advanced various natural language processing tasks but deploying them remains computationally expensive. Knowledge distillation (KD) is a promising solution enabling the transfer of capabilities from larger teacher LLMs to more compact student models. Particularly sequence-level KD which distills rationale-based reasoning processes instead of merely final outcomes shows great potential in enhancing students reasoning capabilities. However current methods struggle with sequence level KD under long-tailed data distributions adversely affecting generalization on sparsely represented domains. We introduce the Multi-Stage Balanced Distillation (BalDistill) framework which iteratively balances training data within a fixed computational budget. By dynamically selecting representative head domain examples and synthesizing tail domain examples BalDistill achieves state-of-the-art performance across diverse long-tailed datasets enhancing both the efficiency and efficacy of the distilled models.
