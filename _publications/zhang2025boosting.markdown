---
layout: publication
title: 'Lax: Boosting Low-rank Training Of Foundation Models Via Latent Crossing'
authors: Ruijie Zhang, Ziyue Liu, Zhengyang Wang, Zheng Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21732"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pre-Training', 'Pretraining Methods']
---
Training foundation models such as ViTs and LLMs requires tremendous computing cost. Low-rank matrix or tensor factorization offers a parameter-efficient alternative, but often downgrades performance due to the restricted parameter space. In this work, we introduce \{\textbf\{Latent Crossing (LaX)\}\} -- a simple yet effective plug-and-play module that enhances the capacity of low-rank models by enabling information flow across low-rank subspaces. We extensively validate the benefits of LaX on pre-training tasks with ViT-Base/Large and LLaMA-like models ranging from 60M to 1B parameters. LaX boosts low-rank model performance to match or exceed the full-rank baselines while using 2-3\(\times\) fewer parameters. When equipped with low-rank adapters (i.e., LoRA) for fine-tuning LLaMA-7/13B, LaX consistently improves performance on arithmetic and common sense reasoning tasks with negligible cost.
