---
layout: publication
title: Latent Positional Information is in the Self-Attention Variance of Transformer Language Models Without Positional Embeddings
authors: Chi Ta-chung, Fan Ting-han, Chen Li-wei, Rudnicky Alexander I., Ramadge Peter J.
conference: "Arxiv"
year: 2023
bibkey: chi2023latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13571"}
tags: ['ARXIV', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
The use of positional embeddings in transformer language models is widely accepted. However recent research has called into question the necessity of such embeddings. We further extend this inquiry by demonstrating that a randomly initialized and frozen transformer language model devoid of positional embeddings inherently encodes strong positional information through the shrinkage of self-attention variance. To quantify this variance we derive the underlying distribution of each step within a transformer layer. Through empirical validation using a fully pretrained model we show that the variance shrinkage effect still persists after extensive gradient updates. Our findings serve to justify the decision to discard positional embeddings and thus facilitate more efficient pretraining of transformer language models.
