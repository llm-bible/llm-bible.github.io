---
layout: publication
title: 'S2-attention: Hardware-aware Context Sharding Among Attention Heads'
authors: Xihui Lin, Yunan Zhang, Suyu Ge, Liliang Ren, Barun Patra, Vishrav Chaudhary, Hao Peng, Xia Song
conference: "Arxiv"
year: 2024
bibkey: lin2024hardware
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.17678'}
tags: ['Attention Mechanism', 'Large-Scale Training', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Reinforcement Learning']
---
Sparse attention, which selectively attends to a subset of tokens in the
context was supposed to be efficient. However, its theoretical reduction in
FLOPs has rarely translated into wall-clock speed-up over its dense attention
counterparts due to the lack of hardware-aware optimizations like
FlashAttention. Meanwhile, it remains unclear whether sparse attention can
maintain the model's quality at a scale of today's large language models (LLMs)
and how. This paper presents Sparsely-Sharded(S2) Attention, a Triton library
that provides kernel optimization for sparse attention customizable at both
per-head and per-context-range levels. S2-Attention enables the exploration of
novel and high-performance sparse attention techniques, which we demonstrate
through extensive ablations across a wide range of sparse attention designs at
various model scales. From these insights, we present several basic guidelines
to design sparse attention that can achieve not only practical efficiency
improvements, but also strong downstream performance. To achieve high
parallelization and optimized memory IO, sparse attention should shard the
context heterogeneously across attention heads, where each head attends to a
different subset of tokens while collectively covering the full context.
Meanwhile, we find hybrid architectures combining sparse and dense attention
particularly beneficial in practice. S2-Attention achieves wall-clock speedup
of 8.79X, 15.87X, 25.3X compared to the strong FlashAttention-2 baseline with
strong downstream performance on-par with full attention and perfect retrieval
performance at a 128k context length. At inference, for 7B models, our model,
with the help of our S2-Attention kernel, achieves 4.5x speed-up compared to
dense counterparts. S2-Attention is released with easy-to-customize APIs for
direct usage in Megatron and vLLM.
