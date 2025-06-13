---
layout: publication
title: 'Pie: Pooling CPU Memory For LLM Inference'
authors: Yi Xu, Ziming Mao, Xiangxi Mo, Shu Liu, Ion Stoica
conference: "Arxiv"
year: 2024
bibkey: xu2024pooling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.09317'}
tags: ['RAG', 'Tools']
---
The rapid growth of LLMs has revolutionized natural language processing and
AI analysis, but their increasing size and memory demands present significant
challenges. A common solution is to spill over to CPU memory; however,
traditional GPU-CPU memory swapping often results in higher latency and lower
throughput.
  This paper introduces Pie, an LLM inference framework that addresses these
challenges with performance-transparent swapping and adaptive expansion. By
leveraging predictable memory access patterns and the high bandwidth of modern
hardware like the NVIDIA GH200 Grace Hopper Superchip, Pie enables concurrent
data swapping without affecting foreground computation, expanding effective
memory without added latency. Adaptive expansion dynamically adjusts CPU memory
allocation based on real-time information, optimizing memory usage and
performance under varying conditions.
  Pie maintains low computation latency, high throughput, and high elasticity.
Our experimental evaluation demonstrates that Pie achieves optimal swapping
policy during cache warmup and effectively balances increased memory capacity
with negligible impact on computation. With its extended capacity, Pie
outperforms vLLM by up to 1.9X in throughput and 2X in latency. Additionally,
Pie can reduce GPU memory usage by up to 1.67X while maintaining the same
performance. Compared to FlexGen, an offline profiling-based swapping solution,
Pie achieves magnitudes lower latency and 9.4X higher throughput.
