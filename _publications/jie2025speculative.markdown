---
layout: publication
title: 'Specache: Speculative Key-value Caching For Efficient Generation Of Llms'
authors: Shibo Jie, Yehui Tang, Kai Han, Zhi-hong Deng, Jing Han
conference: "Arxiv"
year: 2025
bibkey: jie2025speculative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16163"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Large-Scale Training', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
Transformer-based large language models (LLMs) have already achieved
remarkable results on long-text tasks, but the limited GPU memory (VRAM)
resources struggle to accommodate the linearly growing demand for key-value
(KV) cache as the sequence length increases, which has become a bottleneck for
the application of LLMs on long sequences. Existing KV cache compression
methods include eviction, merging, or quantization of the KV cache to reduce
its size. However, compression results in irreversible information forgetting,
potentially affecting the accuracy of subsequent decoding. In this paper, we
propose SpeCache, which takes full advantage of the large and easily expandable
CPU memory to offload the complete KV cache, and dynamically fetches KV pairs
back in each decoding step based on their importance measured by low-bit KV
cache copy in VRAM. To avoid inference latency caused by CPU-GPU communication,
SpeCache speculatively predicts the KV pairs that the next token might attend
to, allowing us to prefetch them before the next decoding step which enables
parallelization of prefetching and computation. Experiments on LongBench and
Needle-in-a-Haystack benchmarks verify that SpeCache effectively reduces VRAM
usage while avoiding information forgetting for long sequences without
re-training, even with a 10x high KV cache compression ratio.
