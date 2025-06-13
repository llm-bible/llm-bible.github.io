---
layout: publication
title: 'PIP: Perturbation-based Iterative Pruning For Large Language Models'
authors: Yi Cao, Wei-jie Xu, Yucheng Shen, Weijie Shi, Chi-min Chan, Jianfeng Qu, Jiajie Xu
conference: "Arxiv"
year: 2025
bibkey: cao2025perturbation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15278"}
tags: ['Tools', 'Efficiency and Optimization', 'Pruning', 'Reinforcement Learning']
---
The rapid increase in the parameter counts of Large Language Models (LLMs), reaching billions or even trillions, presents significant challenges for their practical deployment, particularly in resource-constrained environments. To ease this issue, we propose PIP (Perturbation-based Iterative Pruning), a novel double-view structured pruning method to optimize LLMs, which combines information from two different views: the unperturbed view and the perturbed view. With the calculation of gradient differences, PIP iteratively prunes those that struggle to distinguish between these two views. Our experiments show that PIP reduces the parameter count by approximately 20% while retaining over 85% of the original model's accuracy across varied benchmarks. In some cases, the performance of the pruned model is within 5% of the unpruned version, demonstrating PIP's ability to preserve key aspects of model effectiveness. Moreover, PIP consistently outperforms existing state-of-the-art (SOTA) structured pruning methods, establishing it as a leading technique for optimizing LLMs in environments with constrained resources.
