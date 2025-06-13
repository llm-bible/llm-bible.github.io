---
layout: publication
title: 'Let''s Focus On Neuron: Neuron-level Supervised Fine-tuning For Large Language Model'
authors: Haoyun Xu, Runzhe Zhan, Derek F. Wong, Lidia S. Chao
conference: "Arxiv"
year: 2024
bibkey: xu2024focus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11621"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pruning', 'Pretraining Methods', 'Fine-Tuning']
---
Large Language Models (LLMs) are composed of neurons that exhibit various
behaviors and roles, which become increasingly diversified as models scale.
Recent studies have revealed that not all neurons are active across different
datasets, and this sparsity correlates positively with the task-specific
ability, leading to advancements in model pruning and training efficiency.
Traditional fine-tuning methods engage all parameters of LLMs, which is
computationally expensive and may not be necessary. In contrast,
Parameter-Efficient Fine-Tuning (PEFT) approaches aim to minimize the number of
trainable parameters, yet they still operate at a relatively macro scale (e.g.,
layer-level). We introduce Neuron-Level Fine-Tuning (NeFT), a novel approach
that refines the granularity of parameter training down to the individual
neuron, enabling more precise and computationally efficient model updates. The
experimental results show that NeFT not only exceeded the performance of
full-parameter fine-tuning and PEFT but also provided insights into the
analysis of neurons.
