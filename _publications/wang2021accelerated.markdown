---
layout: publication
title: 'Lightseq2: Accelerated Training For Transformer-based Models On Gpus'
authors: Xiaohui Wang, Yang Wei, Ying Xiong, Guyue Huang, Xian Qian, Yufei Ding, Mingxuan Wang, Lei Li
conference: "Arxiv"
year: 2021
bibkey: wang2021accelerated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2110.05722'}
tags: ['Transformer', 'WMT', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Training Techniques', 'BERT', 'GPT', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Transformer-based neural models are used in many AI applications. Training
these models is expensive, as it takes huge GPU resources and long duration. It
is challenging because typical data like sentences have variable lengths, and
Transformer's computation patterns are more complex than convolutional neural
networks. Existing systems either only focus on model inference or optimization
for only BERT-like encoder models. In this paper, we present LightSeq2, a
system to accelerate training for a general family of Transformer models on
GPUs. We propose a series of GPU optimization techniques tailored to the
specific computation flow and memory access patterns of Transformer models.
LightSeq2 supports many model architectures, including BERT (encoder-only), GPT
(decoder-only), Transformer (encoder-decoder), and vision Transformer. Our
experiments for a variety of models and benchmarks show that LightSeq2 is
consistently faster (1.4-3.5x) than previous systems on different GPUs. In
particular, it gains 308% training speedup compared with existing systems on a
large public machine translation benchmark (WMT14 English-German).
