---
layout: publication
title: 'Saro: Enhancing LLM Safety Through Reasoning-based Alignment'
authors: Yutao Mou, Yuxiao Luo, Shikun Zhang, Wei Ye
conference: "Arxiv"
year: 2025
bibkey: mou2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09420"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Current safety alignment techniques for large language models (LLMs) face two
key challenges: (1) under-generalization, which leaves models vulnerable to
novel jailbreak attacks, and (2) over-alignment, which leads to the excessive
refusal of benign instructions. Our preliminary investigation reveals semantic
overlap between jailbreak/harmful queries and normal prompts in embedding
space, suggesting that more effective safety alignment requires a deeper
semantic understanding. This motivates us to incorporate safety-policy-driven
reasoning into the alignment process. To this end, we propose the
Safety-oriented Reasoning Optimization Framework (SaRO), which consists of two
stages: (1) Reasoning-style Warmup (RW) that enables LLMs to internalize
long-chain reasoning through supervised fine-tuning, and (2) Safety-oriented
Reasoning Process Optimization (SRPO) that promotes safety reflection via
direct preference optimization (DPO). Extensive experiments demonstrate the
superiority of SaRO over traditional alignment methods.
