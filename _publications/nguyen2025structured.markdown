---
layout: publication
title: 'Structured Pruning For Diverse Best-of-n Reasoning Optimization'
authors: Hieu Trung Nguyen, Bao Nguyen, Viet Anh Nguyen
conference: "Arxiv"
year: 2025
bibkey: nguyen2025structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03978"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pruning', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Model pruning in transformer-based language models, traditionally viewed as a means of achieving computational savings, can enhance the model's reasoning capabilities. In this work, we uncover a surprising phenomenon: the selective pruning of certain attention heads leads to improvements in reasoning performance, particularly on challenging tasks. Motivated by this observation, we propose SPRINT, a novel contrastive learning framework that dynamically selects the optimal head and layer to prune during inference. By aligning question embeddings with head embeddings, SPRINT identifies those pruned-head configurations that result in more accurate reasoning. Extensive experiments demonstrate that our method significantly outperforms traditional best-of-\\(N\\) and random head selection strategies on the MATH500 and GSM8K datasets.
