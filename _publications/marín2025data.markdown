---
layout: publication
title: 'APE: A Data-centric Benchmark For Efficient LLM Adaptation In Text Summarization'
authors: Javier Marín
conference: "Arxiv"
year: 2025
bibkey: marín2025data
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19912'}
tags: ['Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
We present Adjacent Possible Exploration (APE), a simple yet effective method for adapting large language models to specific tasks using minimal computational resources. Unlike traditional fine-tuning that requires extensive compute, APE iteratively fine-tunes models on small, carefully selected data batches (200 examples), retaining only improvements. On news summarization, APE achieves 40 percent BLEU improvement using just a T4 GPU in 60 minutes, matching or exceeding more complex methods like LoRA while remaining conceptually simple. Our approach is particularly valuable for researchers and practitioners with limited computational resources. We provide open-source code and demonstrate APE's effectiveness through both automatic metrics and human evaluation. While inspired by evolutionary theory's "adjacent possible", APE's core insight has a very practical application: small, iterative data perturbations can efficiently guide LLMs toward task-specific performance without expensive retraining.
