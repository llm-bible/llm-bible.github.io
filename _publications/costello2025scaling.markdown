---
layout: publication
title: 'Think, Prune, Train, Improve: Scaling Reasoning Without Scaling Models'
authors: Caia Costello, Simon Guo, Anna Goldie, Azalia Mirhoseini
conference: "Arxiv"
year: 2025
bibkey: costello2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18116"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Pruning', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) have demonstrated strong capabilities in
programming and mathematical reasoning tasks, but are constrained by limited
high-quality training data. Synthetic data can be leveraged to enhance
fine-tuning outcomes, but several factors influence this process, including
model size, synthetic data volume, pruning strategy, and number of fine-tuning
rounds. We explore these axes and investigate which conditions enable model
self-improvement. We introduce the Think, Prune, Train process, a scalable
framework that iteratively fine-tunes models on their own reasoning traces,
using ground-truth pruning to ensure high-quality training data. This approach
yields improved performance: on GSM8K, Gemma2-2B achieves a Pass@1 of 57.6%
(from 41.9%), Gemma2-9B reaches 82%, matching LLaMA-3.1-70B, and LLaMA-3.1-70B
attains 91%, even surpassing GPT-4o, demonstrating the effectiveness of
self-generated reasoning and systematic data selection for improving LLM
capabilities.
