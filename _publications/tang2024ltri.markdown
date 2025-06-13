---
layout: publication
title: 'Ltri-llm: Streaming Long Context Inference For Llms With Training-free Dynamic Triangular Attention Pattern'
authors: Hongyin Tang, Di Xiu, Lanrui Wang, Xiurui Geng, Jingang Wang, Xunliang Cai
conference: "Arxiv"
year: 2024
bibkey: tang2024ltri
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04757"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Transformer', 'Attention Mechanism']
---
The quadratic computational complexity of the attention mechanism in current
Large Language Models (LLMs) renders inference with long contexts prohibitively
expensive. To address this challenge, various approaches aim to retain critical
portions of the context to optimally approximate Full Attention (FA) through
Key-Value (KV) compression or Sparse Attention (SA), enabling the processing of
virtually unlimited text lengths in a streaming manner. However, these methods
struggle to achieve performance levels comparable to FA, particularly in
retrieval tasks. In this paper, our analysis of attention head patterns reveals
that LLMs' attention distributions show strong local correlations, naturally
reflecting a chunking mechanism for input context. We propose Ltri-LLM
framework, which divides KVs into spans, stores them in an offline index, and
retrieves the relevant KVs into memory for various queries. Experimental
results on popular long text benchmarks show that Ltri-LLM can achieve
performance close to FA while maintaining efficient, streaming-based inference.
