---
layout: publication
title: 'Adaptive Multi-resolution Attention With Linear Complexity'
authors: Yao Zhang, Yunpu Ma, Thomas Seidl, Volker Tresp
conference: "Arxiv"
year: 2021
bibkey: zhang2021adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.04962"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
Transformers have improved the state-of-the-art across numerous tasks in
sequence modeling. Besides the quadratic computational and memory complexity
w.r.t the sequence length, the self-attention mechanism only processes
information at the same scale, i.e., all attention heads are in the same
resolution, resulting in the limited power of the Transformer. To remedy this,
we propose a novel and efficient structure named Adaptive Multi-Resolution
Attention (AdaMRA for short), which scales linearly to sequence length in terms
of time and space. Specifically, we leverage a multi-resolution multi-head
attention mechanism, enabling attention heads to capture long-range contextual
information in a coarse-to-fine fashion. Moreover, to capture the potential
relations between query representation and clues of different attention
granularities, we leave the decision of which resolution of attention to use to
query, which further improves the model's capacity compared to vanilla
Transformer. In an effort to reduce complexity, we adopt kernel attention
without degrading the performance. Extensive experiments on several benchmarks
demonstrate the effectiveness and efficiency of our model by achieving a
state-of-the-art performance-efficiency-memory trade-off. To facilitate AdaMRA
utilization by the scientific community, the code implementation will be made
publicly available.
