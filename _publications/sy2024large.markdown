---
layout: publication
title: 'Lillama: Large Language Models Compression Via Low-rank Feature Distillation'
authors: Yaya Sy, Christophe Cerisara, Irina Illina
conference: "Arxiv"
year: 2024
bibkey: sy2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.16719'}
tags: ['Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Pruning', 'Pretraining Methods']
---
Current LLM structured pruning methods typically involve two steps: (1)
compression with calibration data and (2) costly continued pretraining on
billions of tokens to recover lost performance. This second step is necessary
as the first significantly impacts model accuracy. Prior research suggests
pretrained Transformer weights aren't inherently low-rank, unlike their
activations, which may explain this drop. Based on this observation, we propose
Lillama, a compression method that locally distills activations with low-rank
weights. Using SVD for initialization and a joint loss combining teacher and
student activations, we accelerate convergence and reduce memory use with local
gradient updates. Lillama compresses Mixtral-8x7B within minutes on a single
A100 GPU, removing 10 billion parameters while retaining over 95% of its
original performance. Phi-2 3B can be compressed by 40% with just 13 million
calibration tokens, resulting in a small model that competes with recent models
of similar size. The method generalizes well to non-transformer architectures,
compressing Mamba-3B by 20% while maintaining 99% performance.
