---
layout: publication
title: 'Clip-moe: Towards Building Mixture Of Experts For CLIP With Diversified Multiplet Upcycling'
authors: Jihai Zhang, Xiaoye Qu, Tong Zhu, Yu Cheng
conference: "Arxiv"
year: 2024
bibkey: zhang2024clip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19291"}
tags: ['Pre-Training', 'Tools', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Contrastive Language-Image Pre-training (CLIP) has become a cornerstone in multimodal intelligence. However, recent studies discovered that CLIP can only encode one aspect of the feature space, leading to substantial information loss and indistinctive features. To mitigate this issue, this paper introduces a novel strategy that fine-tunes a series of complementary CLIP models and transforms them into a CLIP-MoE. Specifically, we propose a model-agnostic Diversified Multiplet Upcycling (DMU) framework for CLIP. Instead of training multiple CLIP models from scratch, DMU leverages a pre-trained CLIP and fine-tunes it into a diverse set with highly cost-effective multistage contrastive learning, thus capturing distinct feature subspaces efficiently. To fully exploit these fine-tuned models while minimizing computational overhead, we transform them into a CLIP-MoE, which dynamically activates a subset of CLIP experts, achieving an effective balance between model capacity and computational cost. Comprehensive experiments demonstrate the superior performance of CLIP-MoE across various zero-shot retrieval, zero-shot image classification tasks, and downstream Multimodal Large Language Model (MLLM) benchmarks when used as a vision encoder.
