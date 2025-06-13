---
layout: publication
title: 'Tensor Product Attention Is All You Need'
authors: Yifan Zhang, Yifeng Liu, Huizhuo Yuan, Zhen Qin, Yang Yuan, Quanquan Gu, Andrew C Yao
conference: "Arxiv"
year: 2025
bibkey: zhang2025tensor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06425"}
  - {name: "Code", url: "https://github.com/tensorgi/T6"}
tags: ['Transformer', 'Efficiency and Optimization', 'Language Modeling', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Scaling language models to handle longer input sequences typically necessitates large key-value (KV) caches, resulting in substantial memory overhead during inference. In this paper, we propose Tensor Product Attention (TPA), a novel attention mechanism that uses tensor decompositions to represent queries, keys, and values compactly, substantially shrinking the KV cache size at inference time. By factorizing these representations into contextual low-rank components and seamlessly integrating with Rotary Position Embedding (RoPE), TPA achieves improved model quality alongside memory efficiency. Based on TPA, we introduce the Tensor Product Attention Transformer,(T6), a new model architecture for sequence modeling. Through extensive empirical evaluation on language modeling tasks, we demonstrate that T6 surpasses or matches the performance of standard Transformer baselines, including Multi-Head Attention (MHA), Multi-Query Attention (MQA), Grouped-Query Attention (GQA), and Multi-Head Latent Attention (MLA) across various metrics, including perplexity and a range of established evaluation benchmarks. Notably, TPA's memory efficiency and computational efficiency at the decoding stage enable processing longer sequences under fixed resource constraints, addressing a critical scalability challenge in modern language models. The code is available at https://github.com/tensorgi/T6.
