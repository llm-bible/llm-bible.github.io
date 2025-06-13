---
layout: publication
title: 'Diversifying The Expert Knowledge For Task-agnostic Pruning In Sparse Mixture-of-experts'
authors: Zeliang Zhang, Xiaodong Liu, Hao Cheng, Chenliang Xu, Jianfeng Gao
conference: "Arxiv"
year: 2024
bibkey: zhang2024diversifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09590"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Pruning', 'Reinforcement Learning', 'Model Architecture', 'Training Techniques']
---
By increasing model parameters but activating them sparsely when performing a
task, the use of Mixture-of-Experts (MoE) architecture significantly improves
the performance of Large Language Models (LLMs) without increasing the
inference cost. However, the memory consumption due to the growing number of
experts presents a challenge to the deployment of these models in many real
world settings. Our empirical study reveals that some experts encode redundant
knowledge during pre-training. We thus propose a method of grouping and pruning
similar experts to improve the model's parameter efficiency. We validate the
effectiveness of our method by pruning three state-of-the-art MoE
architectures, including Mixtral, Deepseek-MoE, and Qwen. The evaluation shows
that our method outperforms other model pruning methods on a range of natural
language tasks. We will release our code to facilitate future research.
