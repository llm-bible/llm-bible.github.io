---
layout: publication
title: 'Gated Slot Attention For Efficient Linear-time Sequence Modeling'
authors: Yu Zhang, Songlin Yang, Ruijie Zhu, Yue Zhang, Leyang Cui, Yiqiao Wang, Bolun Wang, Freda Shi, Bailin Wang, Wei Bi, Peng Zhou, Guohong Fu
conference: "Arxiv"
year: 2024
bibkey: zhang2024gated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07146"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Linear attention Transformers and their gated variants, celebrated for
enabling parallel training and efficient recurrent inference, still fall short
in recall-intensive tasks compared to traditional Transformers and demand
significant resources for training from scratch. This paper introduces Gated
Slot Attention (GSA), which enhances Attention with Bounded-memory-Control
(ABC) by incorporating a gating mechanism inspired by Gated Linear Attention
(GLA). Essentially, GSA comprises a two-layer GLA linked via
\\(\operatorname\{softmax\}\\), utilizing context-aware memory reading and adaptive
forgetting to improve memory capacity while maintaining compact recurrent state
size. This design greatly enhances both training and inference efficiency
through GLA's hardware-efficient training algorithm and reduced state size.
Additionally, retaining the \\(\operatorname\{softmax\}\\) operation is particularly
beneficial in "finetuning pretrained Transformers to RNNs" (T2R) settings,
reducing the need for extensive training from scratch. Extensive experiments
confirm GSA's superior performance in scenarios requiring in-context recall and
in T2R settings.
