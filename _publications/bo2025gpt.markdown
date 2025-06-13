---
layout: publication
title: 'GPT Meets Graphs And KAN Splines: Testing Novel Frameworks On Multitask Fine-tuned GPT-2 With Lora'
authors: Gabriel Bo, Marc Bernardino, Justin Gu
conference: "Arxiv"
year: 2025
bibkey: bo2025gpt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.10490'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'GPT', 'Pretraining Methods']
---
We explore the potential of integrating learnable and interpretable
modules--specifically Kolmogorov-Arnold Networks (KAN) and graph-based
representations--within a pre-trained GPT-2 model to enhance multi-task
learning accuracy. Motivated by the recent surge in using KAN and graph
attention (GAT) architectures in chain-of-thought (CoT) models and debates over
their benefits compared to simpler architectures like MLPs, we begin by
enhancing a standard self-attention transformer using Low-Rank Adaptation
(LoRA), fine-tuning hyperparameters, and incorporating L2 regularization. This
approach yields significant improvements. To further boost interpretability and
richer representations, we develop two variants that attempt to improve the
standard KAN and GAT: Graph LoRA and Hybrid-KAN LoRA (Learnable GPT). However,
systematic evaluations reveal that neither variant outperforms the optimized
LoRA-enhanced transformer, which achieves 55.249% accuracy on the SST test set,
99.18% on the CFIMDB dev set, and 89.9% paraphrase detection test accuracy. On
sonnet generation, we get a CHRF score of 42.097. These findings highlight that
efficient parameter adaptation via LoRA remains the most effective strategy for
our tasks: sentiment analysis, paraphrase detection, and sonnet generation.
