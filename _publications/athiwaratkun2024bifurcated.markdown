---
layout: publication
title: 'Bifurcated Attention: Accelerating Massively Parallel Decoding With Shared Prefixes In Llms'
authors: Ben Athiwaratkun, Sujan Kumar Gonugondla, Sanjay Krishna Gouda, Haifeng Qian, Hantian Ding, Qing Sun, Jun Wang, Jiacheng Guo, Liangfu Chen, Parminder Bhatia, Ramesh Nallapati, Sudipta Sengupta, Bing Xiang
conference: "Arxiv"
year: 2024
bibkey: athiwaratkun2024bifurcated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.08845'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
This study introduces bifurcated attention, a method designed to enhance
language model inference in shared-context batch decoding scenarios. Our
approach addresses the challenge of redundant memory IO costs, a critical
factor contributing to latency in high batch sizes and extended context
lengths. Bifurcated attention achieves this by strategically dividing the
attention mechanism during incremental decoding into two separate GEMM
operations: one focusing on the KV cache from prefill, and another on the
decoding process itself. While maintaining the computational load (FLOPs) of
standard attention mechanisms, bifurcated attention ensures precise computation
with significantly reduced memory IO. Our empirical results show over
2.1\\(\times\\) speedup when sampling 16 output sequences and more than 6.2\\(\times\\)
speedup when sampling 32 sequences at context lengths exceeding 8k tokens on a
7B model that uses multi-head attention. The efficiency gains from bifurcated
attention translate into lower latency, making it particularly suitable for
real-time applications. For instance, it enables massively parallel answer
generation without substantially increasing latency, thus enhancing performance
when integrated with post-processing techniques such as re-ranking.
