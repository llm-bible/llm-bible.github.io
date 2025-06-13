---
layout: publication
title: 'Error Typing For Smarter Rewards: Improving Process Reward Models With Error-aware Hierarchical Supervision'
authors: Tej Deep Pala, Panshul Sharma, Amir Zadeh, Chuan Li, Soujanya Poria
conference: "Arxiv"
year: 2025
bibkey: pala2025error
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19706'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization']
---
Large Language Models (LLMs) are prone to hallucination, especially during multi-hop and reasoning-intensive tasks such as mathematical problem solving. While Outcome Reward Models verify only final answers, Process Reward Models (PRMs) score each intermediate step to steer generation toward coherent solutions. We introduce PathFinder-PRM, a novel hierarchical, error-aware discriminative PRM that first classifies math and consistency errors at each step, then combines these fine-grained signals to estimate step correctness. To train PathFinder-PRM, we construct a 400K-sample dataset by enriching the human-annotated PRM800K corpus and RLHFlow Mistral traces with three-dimensional step-level labels. On PRMBench, PathFinder-PRM achieves a new state-of-the-art PRMScore of 67.7, outperforming the prior best (65.5) while using 3 times less data. When applied to reward guided greedy search, our model yields prm@8 48.3, a +1.5 point gain over the strongest baseline. These results demonstrate that decoupled error detection and reward estimation not only boost fine-grained error detection but also substantially improve end-to-end, reward-guided mathematical reasoning with greater data efficiency.
