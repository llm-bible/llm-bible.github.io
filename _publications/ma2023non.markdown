---
layout: publication
title: 'Non-autoregressive Streaming Transformer For Simultaneous Translation'
authors: Zhengrui Ma, Shaolei Zhang, Shoutao Guo, Chenze Shao, Min Zhang, Yang Feng
conference: "Arxiv"
year: 2023
bibkey: ma2023non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14883"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Transformer', 'Applications']
---
Simultaneous machine translation (SiMT) models are trained to strike a
balance between latency and translation quality. However, training these models
to achieve high quality while maintaining low latency often leads to a tendency
for aggressive anticipation. We argue that such issue stems from the
autoregressive architecture upon which most existing SiMT models are built. To
address those issues, we propose non-autoregressive streaming Transformer
(NAST) which comprises a unidirectional encoder and a non-autoregressive
decoder with intra-chunk parallelism. We enable NAST to generate the blank
token or repetitive tokens to adjust its READ/WRITE strategy flexibly, and
train it to maximize the non-monotonic latent alignment with an alignment-based
latency loss. Experiments on various SiMT benchmarks demonstrate that NAST
outperforms previous strong autoregressive SiMT baselines.
