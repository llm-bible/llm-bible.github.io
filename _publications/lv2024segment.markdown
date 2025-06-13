---
layout: publication
title: 'Critiprefill: A Segment-wise Criticality-based Approach For Prefilling Acceleration In Llms'
authors: Junlin Lv, Yuan Feng, Xike Xie, Xin Jia, Qirong Peng, Guiming Xie
conference: "Arxiv"
year: 2024
bibkey: lv2024segment
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.12490'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Pruning']
---
Large language models have achieved notable success across various domains,
yet efficient inference is still limited by the quadratic computation
complexity of the attention mechanism. The inference consists of prefilling and
decoding phases. Although several attempts have been made to accelerate
decoding, the inefficiency of the prefilling phase, especially for long-context
tasks, remains a challenge. In this paper, we observe a locality in query
criticality during the prefilling phase of long-context processing: adjacent
query tokens tend to focus on similar subsets of the past Key-Value (KV) cache.
Based on this observation, we propose CritiPrefill, a criticality-based
segment-wise prefilling method. This method partitions the input sequence's
queries and KV cache into segments and blocks, utilizing a segment-wise
algorithm to estimate the query criticality. By pruning non-critical
computations between query segments and cache blocks in the self-attention
mechanism, the prefilling process can be significantly accelerated. Extensive
evaluations on multiple long-context datasets show up to 2.7x speedup on
Llama3-8B and 3.0x speedup on Yi-9B for 128K context length on a single A100
GPU, with minimal quality degradation.
