---
layout: publication
title: 'Self-generated Critiques Boost Reward Modeling For Language Models'
authors: Yue Yu, Zhengxing Chen, Aston Zhang, Liang Tan, Chenguang Zhu, Richard Yuanzhe Pang, Yundi Qian, Xuewei Wang, Suchin Gururangan, Chao Zhang, Melanie Kambadur, Dhruv Mahajan, Rui Hou
conference: "NAACL 2025"
year: 2024
bibkey: yu2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16646"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Reward modeling is crucial for aligning large language models (LLMs) with
human preferences, especially in reinforcement learning from human feedback
(RLHF). However, current reward models mainly produce scalar scores and
struggle to incorporate critiques in a natural language format. We hypothesize
that predicting both critiques and the scalar reward would improve reward
modeling ability. Motivated by this, we propose Critic-RM, a framework that
improves reward models using self-generated critiques without extra
supervision. Critic-RM employs a two-stage process: generating and filtering
high-quality critiques, followed by joint fine-tuning on reward prediction and
critique generation. Experiments across benchmarks show that Critic-RM improves
reward modeling accuracy by 3.7%-7.3% compared to standard reward models and
LLM judges, demonstrating strong performance and data efficiency. Additional
studies further validate the effectiveness of generated critiques in rectifying
flawed reasoning steps with 2.5%-3.2% gains in improving reasoning accuracy.
