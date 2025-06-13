---
layout: publication
title: 'N-gram Induction Heads For In-context RL: Improving Stability And Reducing Data Needs'
authors: Ilya Zisman, Alexander Nikulin, Viacheslav Sinii, Denis Tarasov, Nikita Lyubaykin, Andrei Polubarov, Igor Kiselev, Vladislav Kurenkov
conference: "Arxiv"
year: 2024
bibkey: zisman2024n
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.01958'}
tags: ['Attention Mechanism', 'Agentic', 'Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
In-context learning allows models like transformers to adapt to new tasks
from a few examples without updating their weights, a desirable trait for
reinforcement learning (RL). However, existing in-context RL methods, such as
Algorithm Distillation (AD), demand large, carefully curated datasets and can
be unstable and costly to train due to the transient nature of in-context
learning abilities. In this work, we integrated the n-gram induction heads into
transformers for in-context RL. By incorporating these n-gram attention
patterns, we considerably reduced the amount of data required for
generalization and eased the training process by making models less sensitive
to hyperparameters. Our approach matches, and in some cases surpasses, the
performance of AD in both grid-world and pixel-based environments, suggesting
that n-gram induction heads could improve the efficiency of in-context RL.
