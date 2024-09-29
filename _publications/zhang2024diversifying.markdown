---
layout: publication
title: Diversifying The Expert Knowledge For Task45;agnostic Pruning In Sparse Mixture45;of45;experts
authors: Zhang Zeliang, Liu Xiaodong, Cheng Hao, Xu Chenliang, Gao Jianfeng
conference: "Arxiv"
year: 2024
bibkey: zhang2024diversifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09590"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pruning', 'Reinforcement Learning', 'Training Techniques']
---
By increasing model parameters but activating them sparsely when performing a task the use of Mixture45;of45;Experts (MoE) architecture significantly improves the performance of Large Language Models (LLMs) without increasing the inference cost. However the memory consumption due to the growing number of experts presents a challenge to the deployment of these models in many real world settings. Our empirical study reveals that some experts encode redundant knowledge during pre45;training. We thus propose a method of grouping and pruning similar experts to improve models parameter efficiency. We validate the effectiveness of our method by pruning two state45;of45;the45;art MoE models Mixtral45;8x7B and Mixtral45;8x22B. Evaluation shows that our method outperforms other model pruning methods on a range of natural language tasks. To facilitate future research we will release our code and the pruned MoE models.
