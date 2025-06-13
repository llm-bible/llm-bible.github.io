---
layout: publication
title: 'Infor-coef: Information Bottleneck-based Dynamic Token Downsampling For Compact And Efficient Language Model'
authors: Wenxi Tan
conference: "Arxiv"
year: 2023
bibkey: tan2023infor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12458"}
tags: ['Transformer', 'Efficiency and Optimization', 'Pruning', 'Model Architecture', 'Pretraining Methods', 'BERT']
---
The prevalence of Transformer-based pre-trained language models (PLMs) has
led to their wide adoption for various natural language processing tasks.
However, their excessive overhead leads to large latency and computational
costs. The statically compression methods allocate fixed computation to
different samples, resulting in redundant computation. The dynamic token
pruning method selectively shortens the sequences but are unable to change the
model size and hardly achieve the speedups as static pruning. In this paper, we
propose a model accelaration approaches for large language models that
incorporates dynamic token downsampling and static pruning, optimized by the
information bottleneck loss. Our model, Infor-Coef, achieves an 18x FLOPs
speedup with an accuracy degradation of less than 8% compared to BERT. This
work provides a promising approach to compress and accelerate transformer-based
models for NLP tasks.
