---
layout: publication
title: 'M-wanda: Improving One-shot Pruning For Multilingual Llms'
authors: Rochelle Choenni, Ivan Titov
conference: "Arxiv"
year: 2025
bibkey: choenni2025m
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21171"}
tags: ['Pretraining Methods', 'Efficiency and Optimization', 'Training Techniques', 'Pruning']
---
Multilingual LLM performance is often critically dependent on model size. With an eye on efficiency, this has led to a surge in interest in one-shot pruning methods that retain the benefits of large-scale pretraining while shrinking the model size. However, as pruning tends to come with performance loss, it is important to understand the trade-offs between multilinguality and sparsification. In this work, we study multilingual performance under different sparsity constraints and show that moderate ratios already substantially harm performance. To help bridge this gap, we propose M-Wanda, a pruning method that models cross-lingual variation by incorporating language-aware activation statistics into its pruning criterion and dynamically adjusts layerwise sparsity based on cross-lingual importance. We show that M-Wanda consistently improves performance at minimal additional costs. We are the first to explicitly optimize pruning to retain multilingual performance, and hope to inspire future advances in multilingual pruning.
