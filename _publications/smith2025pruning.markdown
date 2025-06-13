---
layout: publication
title: 'Flexigpt: Pruning And Extending Large Language Models With Low-rank Weight Sharing'
authors: James Seale Smith, Chi-heng Lin, Shikhar Tuli, Haris Jeelani, Shangqian Gao, Yilin Shen, Hongxia Jin, Yen-chang Hsu
conference: "Arxiv"
year: 2025
bibkey: smith2025pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14713"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Pruning', 'Training Techniques']
---
The rapid proliferation of large language models (LLMs) in natural language
processing (NLP) has created a critical need for techniques that enable
efficient deployment on memory-constrained devices without compromising
performance. We present a method to prune LLMs that selectively prunes model
blocks based on an importance score and replaces them with a low-parameter
replacement strategy. Specifically, we propose a principled metric to replace
each pruned block using a weight-sharing mechanism that leverages unpruned
counterparts from the model and block-specific low-rank adapters. Furthermore,
we facilitate the learning of these replacement blocks with output feature
normalization and an adapter initialization scheme built on low-rank SVD
reconstructions. Empirical evaluations demonstrate substantial performance
gains over existing methods, achieving state-of-the-art performance on 5/6
benchmarks for a compression rate of 30% and 6/6 benchmarks for a compression
rate of 40%. We also demonstrate that our approach can extend smaller models,
boosting performance on 6/6 benchmarks using only ~0.3% tokens of extended
training with minimal additional parameter costs.
