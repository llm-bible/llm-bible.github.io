---
layout: publication
title: 'Gated Delta Networks: Improving Mamba2 With Delta Rule'
authors: Songlin Yang, Jan Kautz, Ali Hatamizadeh
conference: "Arxiv"
year: 2024
bibkey: yang2024gated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06464"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Linear Transformers have gained attention as efficient alternatives to
standard Transformers, but their performance in retrieval and long-context
tasks has been limited. To address these limitations, recent work has explored
two distinct mechanisms: gating for adaptive memory control and the delta
update rule for precise memory modifications. We observe that these mechanisms
are complementary: gating enables rapid memory erasure while the delta rule
facilitates targeted updates. Building on this insight, we introduce the gated
delta rule and develop a parallel training algorithm optimized for modern
hardware. Our proposed architecture, Gated DeltaNet, consistently surpasses
existing models like Mamba2 and DeltaNet across multiple benchmarks, including
language modeling, common-sense reasoning, in-context retrieval, length
extrapolation, and long-context understanding. We further enhance performance
by developing hybrid architectures that combine Gated DeltaNet layers with
sliding window attention or Mamba2 layers, achieving both improved training
efficiency and superior task performance.
