---
layout: publication
title: 'Multi-granularity Knowledge Transfer For Continual Reinforcement Learning'
authors: Chaofan Pan, Lingfei Ren, Yihui Feng, Linbo Xiong, Wei Wei, Yonghao Li, Xin Yang
conference: "Arxiv"
year: 2024
bibkey: pan2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.15098'}
tags: ['Reinforcement Learning', 'Agentic', 'Tools']
---
Continual reinforcement learning (CRL) empowers RL agents with the ability to learn a sequence of tasks, accumulating knowledge learned in the past and using the knowledge for problemsolving or future task learning. However, existing methods often focus on transferring fine-grained knowledge across similar tasks, which neglects the multi-granularity structure of human cognitive control, resulting in insufficient knowledge transfer across diverse tasks. To enhance coarse-grained knowledge transfer, we propose a novel framework called MT-Core (as shorthand for Multi-granularity knowledge Transfer for Continual reinforcement learning). MT-Core has a key characteristic of multi-granularity policy learning: 1) a coarsegrained policy formulation for utilizing the powerful reasoning ability of the large language model (LLM) to set goals, and 2) a fine-grained policy learning through RL which is oriented by the goals. We also construct a new policy library (knowledge base) to store policies that can be retrieved for multi-granularity knowledge transfer. Experimental results demonstrate the superiority of the proposed MT-Core in handling diverse CRL tasks versus popular baselines.
