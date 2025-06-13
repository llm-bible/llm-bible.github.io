---
layout: publication
title: 'Floe: Fisher-based Layer Selection For Efficient Sparse Adaptation Of Low-rank Experts'
authors: Xinyi Wang, Lirong Gao, Haobo Wang, Yiming Zhang, Junbo Zhao
conference: "Arxiv"
year: 2025
bibkey: wang2025fisher
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00495'}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Parameter-Efficient Fine-Tuning (PEFT) methods have emerged as a widely adopted strategy for adapting pre-trained Large Language Models (LLMs) to downstream tasks, significantly reducing memory and computational costs. However, most existing PEFT techniques uniformly deploy LoRA adapters across all layers, disregarding the intrinsic heterogeneity of layer contributions and task-specific rank requirements. This uniform paradigm leads to redundant parameter allocation and suboptimal adaptation efficiency. To address these limitations, we propose FLoE, a novel PEFT framework that introduces two key innovations: (i) a Fisher information-guided importance scoring mechanism to dynamically identify task-critical transformer layers for MoE-based low-rank adaptation, enabling sparse adapter deployment; and (ii) a Bayesian optimization-driven rank allocator that automatically determines optimal LoRA ranks on specific datasets without exhaustive grid search. Extensive experiments across diverse LLMs and benchmarks reveal that FLoE achieves impressive efficiency-accuracy trade-offs, making FLoE particularly advantageous in resource-constrained environments that necessitate rapid adaptation.
