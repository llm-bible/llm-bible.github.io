---
layout: publication
title: Efficient LLM Training And Serving With Heterogeneous Context Sharding Among Attention Heads
authors: Lin Xihui, Zhang Yunan, Ge Suyu, Patra Barun, Chaudhary Vishrav, Peng Hao, Song Xia
conference: "Arxiv"
year: 2024
bibkey: lin2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17678"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Existing LLM training and inference frameworks struggle in boosting efficiency with sparsity while maintaining the integrity of context and model architecture. Inspired by the sharding concept in database and the fact that attention parallelizes over heads on accelerators we propose Sparsely45;Sharded (S2) Attention an attention algorithm that allocates heterogeneous context partitions for different attention heads to divide and conquer. S245;Attention enforces each attention head to only attend to a partition of contexts following a strided sparsity pattern while the full context is preserved as the union of all the shards. As attention heads are processed in separate thread blocks the context reduction for each head can thus produce end45;to45;end speed45;up and memory reduction. At inference LLMs trained with S245;Attention can then take the KV cache reduction as free meals with guaranteed model quality preserve. In experiments we show S245;Attentioncan provide as much as (1) 25.3X wall45;clock attention speed45;up over FlashAttention45;2 resulting in 6X reduction in end45;to45;end training time and 10X inference latency (2) on45;par model training quality compared to default attention (3)perfect needle retrieval accuracy over 32K context window. On top of the algorithm we build DKernel an LLM training and inference kernel library that allows users to customize sparsity patterns for their own models. We open45;sourced DKerneland make it compatible with Megatron Pytorch and vLLM.
