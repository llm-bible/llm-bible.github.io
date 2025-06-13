---
layout: publication
title: 'Minimizing Plm-based Few-shot Intent Detectors'
authors: Haode Zhang, Albert Y. S. Lam, Xiao-ming Wu
conference: "Arxiv"
year: 2024
bibkey: zhang2024minimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09943"}
tags: ['Transformer', 'Efficiency and Optimization', 'Pruning', 'Reinforcement Learning', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Distillation']
---
Recent research has demonstrated the feasibility of training efficient intent
detectors based on pre-trained language model~(PLM) with limited labeled data.
However, deploying these detectors in resource-constrained environments such as
mobile devices poses challenges due to their large sizes. In this work, we aim
to address this issue by exploring techniques to minimize the size of PLM-based
intent detectors trained with few-shot data. Specifically, we utilize large
language models (LLMs) for data augmentation, employ a cutting-edge model
compression method for knowledge distillation, and devise a vocabulary pruning
mechanism called V-Prune. Through these approaches, we successfully achieve a
compression ratio of 21 in model memory usage, including both Transformer and
the vocabulary, while maintaining almost identical performance levels on four
real-world benchmarks.
