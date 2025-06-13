---
layout: publication
title: 'Personalized Federated Fine-tuning For Heterogeneous Data: An Automatic Rank Learning Approach Via Two-level Lora'
authors: Jie Hao, Yuman Wu, Ali Payani, Myungjin Lee, Mingrui Liu
conference: "Arxiv"
year: 2025
bibkey: hao2025personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03920"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Applications']
---
We study the task of personalized federated fine-tuning with heterogeneous
data in the context of language models, where clients collaboratively fine-tune
a language model (e.g., BERT, GPT) without sharing their local data, achieving
personalization simultaneously. While recent efforts have applied
parameter-efficient fine-tuning techniques like low-rank adaptation (LoRA) in
federated settings, they typically use single or multiple independent low-rank
adapters with predefined maximal and minimal ranks, which may not be optimal
for diverse data sources over clients.
  To address this issue, we propose PF2LoRA, a new personalized federated
fine-tuning algorithm built on a novel *automatic rank learning approach
via two-level LoRA*. Given the pretrained language model whose weight is
frozen, our algorithm aims to learn two levels of adaptation simultaneously:
the first level aims to learn a common adapter for all clients, while the
second level fosters individual client personalization. A key advantage of
PF2LoRA is its ability to adaptively determine a suitable rank based on an
individual client's data, rather than relying on a predefined rank that is
agnostic to data heterogeneity. We present a synthetic example that highlights
how PF2LoRA automatically learns the ground-truth rank for each client,
tailoring the adaptation to match the properties of their individual data.
Notably, this approach introduces minimal additional memory overhead, as the
second-level adaptation comprises a small number of parameters compared to the
first level. Our experiments on natural language understanding and generation
tasks demonstrate that PF2LoRA significantly outperforms existing federated
fine-tuning methods.
