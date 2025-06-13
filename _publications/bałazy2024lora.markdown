---
layout: publication
title: 'Lora-xs: Low-rank Adaptation With Extremely Small Number Of Parameters'
authors: Klaudia Bałazy, Mohammadreza Banaei, Karl Aberer, Jacek Tabor
conference: "Arxiv"
year: 2024
bibkey: bałazy2024lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17604"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Transformer']
---
The rapid expansion of large language models (LLMs) has underscored the need
for parameter-efficient fine-tuning methods, with LoRA (Low-Rank Adaptation)
emerging as a popular solution. Although LoRA reduces the number of trainable
parameters, serving multiple (task or user-specific) LoRA modules on top of a
base model still creates significant storage challenges. To address this, using
theoretical derivation, we introduce LoRA-XS (Low-Rank Adaptation with
eXtremely Small number of parameters), a novel low-rank adaptation method that
considerably reduces the trainable parameters while showing superior or
competitive performance. LoRA-XS achieves this by inserting a small, trainable
r x r weight matrix between frozen low-rank matrices, which are constructed by
Singular Value Decomposition (SVD) of the original weight matrix. This
lightweight matrix enables fine-tuning with drastically reduced storage
requirements, making it feasible to deploy millions of personalized models
while minimizing memory overhead. For instance, LoRA-XS achieves a remarkable
reduction of trainable parameters by over 100x in 7B models compared to LoRA.
Our evaluations across various benchmarks (including GLUE, GSM8K, MATH, and
eight commonsense reasoning datasets) demonstrate that LoRA-XS performs
competitively or better than LoRA and other recent methods like VeRA while
being significantly more parameter efficient. We also provide an extensive
ablation study on the importance of singular vectors in transformer weights,
shedding light on the underlying mechanisms driving LoRA-XS's enhanced
efficiency. These findings suggest that LoRA-XS is not only a storage-efficient
alternative, but also a powerful tool for scaling and personalizing LLMs at
unprecedented scales.
