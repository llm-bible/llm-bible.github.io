---
layout: publication
title: 'Baklava -- Budgeted Allocation Of KV Cache For Long-context Inference'
authors: Ahmed Burak Gulhan, Krishna Teja Chitty-venkata, Murali Emani, Mahmut Kandemir, Venkatram Vishwanath
conference: "Arxiv"
year: 2025
bibkey: gulhan2025baklava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13176"}
tags: ['Model Architecture', 'Attention Mechanism']
---
In Large Language Model (LLM) inference, Key-Value (KV) caches (KV-caches)
are essential for reducing time complexity. However, they result in a linear
increase in GPU memory as the context length grows. While recent work explores
KV-cache eviction and compression policies to reduce memory usage, they often
consider uniform KV-caches across all attention heads, leading to suboptimal
performance. We introduce BaKlaVa, a method to allocate optimal memory for
individual KV-caches across the model by estimating the importance of each
KV-cache. Our empirical analysis demonstrates that not all KV-caches are
equally critical for LLM performance. Using a one-time profiling approach,
BaKlaVa assigns optimal memory budgets to each KV-cache. We evaluated our
method on LLaMA-3-8B, and Qwen2.5-7B models, achieving up to a 70% compression
ratio while keeping baseline performance and delivering up to an
order-of-magnitude accuracy improvement at higher compression levels.
