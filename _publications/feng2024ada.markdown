---
layout: publication
title: 'Ada-kv: Optimizing KV Cache Eviction By Adaptive Budget Allocation For Efficient LLM Inference'
authors: Yuan Feng, Junlin Lv, Yukun Cao, Xike Xie, S. Kevin Zhou
conference: "Arxiv"
year: 2024
bibkey: feng2024ada
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11550"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism']
---
Large Language Models have excelled in various domains but face efficiency
challenges due to the growing Key-Value (KV) cache required for long-sequence
inference. Recent efforts aim to reduce KV cache size by evicting vast
non-critical cache elements during runtime while preserving generation quality.
However, these methods typically allocate compression budgets uniformly across
all attention heads, ignoring the unique attention patterns of each head. In
this paper, we establish a theoretical loss upper bound between pre- and
post-eviction attention output, explaining the optimization target of prior
cache eviction methods, while guiding the optimization of adaptive budget
allocation. Base on this, we propose \{\it Ada-KV\}, the first head-wise adaptive
budget allocation strategy. It offers plug-and-play benefits, enabling seamless
integration with prior cache eviction methods. Extensive evaluations on 13
datasets from Ruler and 16 datasets from LongBench, all conducted under both
question-aware and question-agnostic scenarios, demonstrate substantial quality
improvements over existing methods.
