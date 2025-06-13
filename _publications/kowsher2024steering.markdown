---
layout: publication
title: 'Propulsion: Steering LLM With Tiny Fine-tuning'
authors: Md Kowsher, Nusrat Jahan Prottasha, Prakash Bhat
conference: "Arxiv"
year: 2024
bibkey: kowsher2024steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10927"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
The rapid advancements in Large Language Models (LLMs) have revolutionized
natural language processing (NLP) and related fields. However, fine-tuning
these models for specific tasks remains computationally expensive and risks
degrading pre-learned features. To address these challenges, we propose
Propulsion, a novel parameter efficient fine-tuning (PEFT) method designed to
optimize task-specific performance while drastically reducing computational
overhead. Inspired by the concept of controlled adjustments in physical motion,
Propulsion selectively re-scales specific dimensions of a pre-trained model,
guiding output predictions toward task objectives without modifying the model's
parameters. By introducing lightweight, trainable Propulsion parameters at the
pre-trained layer, we minimize the number of parameters updated during
fine-tuning, preventing overfitting or overwriting of existing knowledge. Our
theoretical analysis, supported by Neural Tangent Kernel (NTK) theory, shows
that Propulsion approximates the performance of full fine-tuning with far fewer
trainable parameters. Empirically, Propulsion reduces the parameter count from
355.3 million to just 0.086 million, achieving over a 10x reduction compared to
standard approaches like LoRA while maintaining competitive performance across
benchmarks.
