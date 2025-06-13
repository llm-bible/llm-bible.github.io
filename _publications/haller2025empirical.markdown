---
layout: publication
title: 'Empirical Evaluation Of Knowledge Distillation From Transformers To Subquadratic Language Models'
authors: Patrick Haller, Jonas Golde, Alan Akbik
conference: "Arxiv"
year: 2025
bibkey: haller2025empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14366"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'RAG', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Attention Mechanism']
---
Knowledge distillation is a widely used technique for compressing large language models (LLMs), in which a smaller student model is trained to mimic a larger teacher model. Typically, both the teacher and student models are Transformer-based architectures, leveraging softmax attention for sequence modeling. However, the quadratic complexity of self-attention during inference remains a significant bottleneck, motivating the exploration of subquadratic alternatives such as structured state-space models (SSMs), linear attention, and recurrent architectures. In this work, we systematically evaluate the transferability of knowledge distillation from a Transformer teacher model to eight subquadratic student architectures. Our study investigates which subquadratic model can most effectively approximate the teacher model's learned representations through knowledge distillation, and how different architectural design choices influence the training dynamics. We further investigate the impact of initialization strategies, such as matrix mixing and query-key-value (QKV) copying, on the adaptation process. Our empirical results on multiple NLP benchmarks provide insights into the trade-offs between efficiency and performance, highlighting key factors for successful knowledge transfer to subquadratic architectures.
