---
layout: publication
title: 'Infopo: On Mutual Information Maximization For Large Language Model Alignment'
authors: Teng Xiao, Zhen Ge, Sujay Sanghavi, Tian Wang, Julian Katz-samuels, Marc Versage, Qingjun Cui, Trishul Chilimbi
conference: "Arxiv"
year: 2025
bibkey: xiao2025mutual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.08507"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
We study the post-training of large language models (LLMs) with human preference data. Recently, direct preference optimization and its variants have shown considerable promise in aligning language models, eliminating the need for reward models and online sampling. Despite these benefits, these methods rely on explicit assumptions about the Bradley-Terry (BT) model, which makes them prone to overfitting and results in suboptimal performance, particularly on reasoning-heavy tasks. To address these challenges, we propose a principled preference fine-tuning algorithm called InfoPO, which effectively and efficiently aligns large language models using preference data. InfoPO eliminates the reliance on the BT model and prevents the likelihood of the chosen response from decreasing. Extensive experiments confirm that InfoPO consistently outperforms established baselines on widely used open benchmarks, particularly in reasoning tasks.
