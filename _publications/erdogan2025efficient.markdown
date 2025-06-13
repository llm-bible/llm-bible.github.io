---
layout: publication
title: 'Efficient Large Language Model Inference With Neural Block Linearization'
authors: Mete Erdogan, Francesco Tonin, Volkan Cevher
conference: "Arxiv"
year: 2025
bibkey: erdogan2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21077'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
The high inference demands of transformer-based Large Language Models (LLMs) pose substantial challenges in their deployment. To this end, we introduce Neural Block Linearization (NBL), a novel framework for accelerating transformer model inference by replacing self-attention layers with linear approximations derived from Linear Minimum Mean Squared Error estimators. NBL leverages Canonical Correlation Analysis to compute a theoretical upper bound on the approximation error. Then, we use this bound as a criterion for substitution, selecting the LLM layers with the lowest linearization error. NBL can be efficiently applied to pre-trained LLMs without the need for fine-tuning. In experiments, NBL achieves notable computational speed-ups while preserving competitive accuracy on multiple reasoning benchmarks. For instance, applying NBL to 12 self-attention layers in DeepSeek-R1-Distill-Llama-8B increases the inference speed by 32% with less than 1% accuracy trade-off, making it a flexible and promising solution to improve the inference efficiency of LLMs.
