---
layout: publication
title: 'GVPO: Group Variance Policy Optimization For Large Language Model Post-training'
authors: Kaichen Zhang, Yuzhong Hong, Junwei Bao, Hongfei Jiang, Yang Song, Dingqian Hong, Hui Xiong
conference: "Arxiv"
year: 2025
bibkey: zhang2025group
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19599"}
tags: ['RAG', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Post-training plays a crucial role in refining and aligning large language models to meet specific tasks and human preferences. While recent advancements in post-training techniques, such as Group Relative Policy Optimization (GRPO), leverage increased sampling with relative reward scoring to achieve superior performance, these methods often suffer from training instability that limits their practical adoption. To address this challenge, we present Group Variance Policy Optimization (GVPO). GVPO incorporates the analytical solution to KL-constrained reward maximization directly into its gradient weights, ensuring alignment with the optimal policy. The method provides intuitive physical interpretations: its gradient mirrors the mean squared error between the central distance of implicit rewards and that of actual rewards. GVPO offers two key advantages: (1) it guarantees a unique optimal solution, exactly the KL-constrained reward maximization objective, (2) it supports flexible sampling distributions that avoids on-policy and importance sampling limitations. By unifying theoretical guarantees with practical adaptability, GVPO establishes a new paradigm for reliable and versatile LLM post-training.
