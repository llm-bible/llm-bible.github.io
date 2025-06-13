---
layout: publication
title: 'Rec-r1: Bridging Generative Large Language Models And User-centric Recommendation Systems Via Reinforcement Learning'
authors: Jiacheng Lin, Tian Wang, Kun Qian
conference: "Arxiv"
year: 2025
bibkey: lin2025rec
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.24289'}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
We propose Rec-R1, a general reinforcement learning framework that bridges large language models (LLMs) with recommendation systems through closed-loop optimization. Unlike prompting and supervised fine-tuning (SFT), Rec-R1 directly optimizes LLM generation using feedback from a fixed black-box recommendation model, without relying on synthetic SFT data from proprietary models such as GPT-4o. This avoids the substantial cost and effort required for data distillation. To verify the effectiveness of Rec-R1, we evaluate it on two representative tasks: product search and sequential recommendation. Experimental results demonstrate that Rec-R1 not only consistently outperforms prompting- and SFT-based methods, but also achieves significant gains over strong discriminative baselines, even when used with simple retrievers such as BM25. Moreover, Rec-R1 preserves the general-purpose capabilities of the LLM, unlike SFT, which often impairs instruction-following and reasoning. These findings suggest Rec-R1 as a promising foundation for continual task-specific adaptation without catastrophic forgetting.
