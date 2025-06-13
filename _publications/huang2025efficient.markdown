---
layout: publication
title: 'Specserve: Efficient And Slo-aware Large Language Model Serving With Adaptive Speculative Decoding'
authors: Kaiyu Huang, Hao Wu, Zhubo Shi, Han Zou, Minchen Yu, Qingjiang Shi
conference: "Arxiv"
year: 2025
bibkey: huang2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05096"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning']
---
Large Language Model (LLM) services often face challenges in achieving low
inference latency and meeting Service Level Objectives (SLOs) under dynamic
request patterns. Speculative decoding, which exploits lightweight models for
drafting and LLMs for verification, has emerged as a compelling technique to
accelerate LLM inference. However, existing speculative decoding solutions
often fail to adapt to varying workloads and system environments, resulting in
performance variability and SLO violations. In this paper, we introduce
SpecServe, an efficient LLM inference system that dynamically adjusts
speculative strategies according to real-time request loads and system
configurations. SpecServe proposes a theoretical model to understand and
predict the efficiency of speculative decoding across diverse scenarios.
Additionally, it implements intelligent drafting and verification algorithms to
guarantee optimal performance while achieving high SLO attainment. Experimental
results on real-world LLM traces demonstrate that SpecServe consistently meets
SLOs and achieves substantial performance improvements, yielding
1.14\\(\times\\)-14.3\\(\times\\) speedups over state-of-the-art speculative inference
systems.
