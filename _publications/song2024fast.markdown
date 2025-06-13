---
layout: publication
title: 'Promoe: Fast Moe-based LLM Serving Using Proactive Caching'
authors: Xiaoniu Song, Zihang Zhong, Rong Chen, Haibo Chen
conference: "Arxiv"
year: 2024
bibkey: song2024fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22134"}
tags: ['RAG', 'Applications']
---
The promising applications of large language models are often limited by the
constrained GPU memory capacity available on edge devices. Mixture-of-Experts
(MoE) models help address this issue by activating only a subset of the model's
parameters during computation. This approach allows the unused parameters to be
offloaded to host memory, thereby reducing the overall GPU memory demand.
However, existing cache-based offloading solutions handle cache misses
reactively, which significantly impacts system performance. In this paper, we
introduce ProMoE, a novel proactive caching system that utilizes intermediate
results to predict subsequent expert usage. By proactively fetching experts in
advance, ProMoE eliminates passive cache misses, removes loading time from the
critical path, and reduces the performance overhead associated with offloading.
Our evaluations demonstrate that ProMoE achieves an average speedup of 2.20x
(up to 3.21x) and 2.07x (up to 5.02x) in the prefill and decode stages,
respectively, compared to existing offloading solutions.
