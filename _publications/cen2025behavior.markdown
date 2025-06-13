---
layout: publication
title: 'Behavior Injection: Preparing Language Models For Reinforcement Learning'
authors: Zhepeng Cen, Yihang Yao, William Han, Zuxin Liu, Ding Zhao
conference: "Arxiv"
year: 2025
bibkey: cen2025behavior
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18917'}
tags: ['Agentic', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Reinforcement fine-tuning (RFT) has emerged as a powerful post-training technique to incentivize the reasoning ability of large language models (LLMs). However, LLMs can respond very inconsistently to RFT: some show substantial performance gains, while others plateau or even degrade. To understand this divergence, we analyze the per-step influence of the RL objective and identify two key conditions for effective post-training: (1) RL-informative rollout accuracy, and (2) strong data co-influence, which quantifies how much the training data affects performance on other samples. Guided by these insights, we propose behavior injection, a task-agnostic data-augmentation scheme applied prior to RL. Behavior injection enriches the supervised finetuning (SFT) data by seeding exploratory and exploitative behaviors, effectively making the model more RL-ready. We evaluate our method across two reasoning benchmarks with multiple base models. The results demonstrate that our theoretically motivated augmentation can significantly increases the performance gain from RFT over the pre-RL model.
