---
layout: publication
title: 'Zsmerge: Zero-shot KV Cache Compression For Memory-efficient Long-context Llms'
authors: Xin Liu, Pei Liu, Guoming Tang
conference: "Arxiv"
year: 2025
bibkey: liu2025zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10714"}
  - {name: "Code", url: "https://github.com/SusCom-Lab/ZSMerge"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Pruning', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Has Code']
---
The linear growth of key-value (KV) cache memory and quadratic computational
in attention mechanisms complexity pose significant bottlenecks for large
language models (LLMs) in long-context processing. While existing KV cache
optimization methods address these challenges through token pruning or feature
merging, they often incur irreversible information loss or require costly
parameter retraining. To this end, we propose ZSMerge, a dynamic KV cache
compression framework designed for efficient cache management, featuring three
key operations: (1) fine-grained memory allocation guided by multi-dimensional
token importance metrics at head-level granularity, (2) a residual merging
mechanism that preserves critical context through compensated attention
scoring, and (3) a zero-shot adaptation mechanism compatible with diverse LLM
architectures without requiring retraining. ZSMerge significantly enhances
memory efficiency and inference speed with negligible performance degradation
across LLMs. When applied to LLaMA2-7B, it demonstrates a 20:1 compression
ratio for key-value cache retention (reducing memory footprint to 5% of
baseline) while sustaining comparable generation quality, coupled with triple
throughput gains at extreme 54k-token contexts that eliminate out-of-memory
failures. The code is available at https://github.com/SusCom-Lab/ZSMerge.
