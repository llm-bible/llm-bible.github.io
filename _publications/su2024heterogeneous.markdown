---
layout: publication
title: 'HAFLQ: Heterogeneous Adaptive Federated Lora Fine-tuned LLM With Quantization'
authors: Yang Su, Na Yan, Yansha Deng, Mischa Dohler, Robert Schober
conference: "Arxiv"
year: 2024
bibkey: su2024heterogeneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06581"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
Federated fine-tuning of pre-trained Large Language Models (LLMs) enables task-specific adaptation across diverse datasets while preserving privacy. However, challenges such as high computational and memory demands, heterogeneous client resources, bandwidth constraints, and ineffective global aggregation hinder its efficiency. To address these issues, we propose HAFLQ (Heterogeneous Adaptive Federated Low-Rank Adaptation Fine-tuned LLM with Quantization), a novel framework for efficient and scalable federated fine-tuning of LLMs in heterogeneous environments. To reduce memory and computation demands, we propose a salience-driven adaptive LLM quantization framework that evaluates the importance of transformer blocks using a salience metric and applies adaptive block-wise quantization accordingly. To handle heterogeneous computational capabilities, we propose an importance-based parameter truncation and freezing scheme. To address communication bottlenecks, we propose an importance-aware bandwidth-adaptive quantization method, which dynamically adjusts parameter precision based on importance and bandwidth constraints. To improve global model aggregation, we propose an adaptive rank-1 matrix-level aggregation strategy, which prevents information dilution and accelerates convergence by aggregating only updated rank-1 matrices from clients. Experimental results on the text classification task demonstrate that HAFLQ reduces memory usage by 31%, lowers communication cost by 49%, improves accuracy by 50%, and achieves faster convergence compared to the baseline method.
