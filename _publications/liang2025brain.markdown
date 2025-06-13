---
layout: publication
title: 'Triadaptlora: Brain-inspired Triangular Adaptive Low-rank Adaptation For Parameter-efficient Fine-tuning'
authors: Yao Liang, Yuwei Wang, Yi Zeng
conference: "Arxiv"
year: 2025
bibkey: liang2025brain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.08008'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The fine-tuning of Large Language Models (LLMs) is pivotal for achieving
optimal performance across diverse downstream tasks. However, while full
fine-tuning delivers superior results, it entails significant computational and
resource costs. Parameter-Efficient Fine-Tuning (PEFT) methods, such as LoRA,
address these challenges by reducing the number of trainable parameters, but
they often struggle with rank adjustment efficiency and task-specific
adaptability. We propose Triangular Adaptive Low-Rank Adaptation
(TriAdaptLoRA), a novel PEFT framework inspired by neuroscience principles,
which dynamically optimizes the allocation of trainable parameters.
TriAdaptLoRA introduces three key innovations: 1) a triangular split of
transformation matrices into lower and upper triangular components to maximize
parameter utilization, 2) a parameter importance metric based on normalized
Frobenius norms for efficient adaptation, and 3) an adaptive rank-growth
strategy governed by dynamic thresholds, allowing flexible parameter allocation
across training steps. Experiments conducted on a variety of natural language
understanding and generation tasks demonstrate that TriAdaptLoRA consistently
outperforms existing PEFT methods. It achieves superior performance, enhanced
stability, and reduced computational overhead, particularly under linear
threshold-driven rank growth. These results highlight its efficacy as a
scalable and resource-efficient solution for fine-tuning LLMs.
