---
layout: publication
title: 'Tlora: Tri-matrix Low-rank Adaptation Of Large Language Models'
authors: Tanvir Islam
conference: "Arxiv"
year: 2025
bibkey: islam2025tri
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18735"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
We propose TLoRA, a novel tri-matrix low-rank adaptation method that
decomposes weight updates into three matrices: two fixed random matrices and
one trainable matrix, combined with a learnable, layer-wise scaling factor.
This tri-matrix design enables TLoRA to achieve highly efficient parameter
adaptation while introducing minimal additional computational overhead. Through
extensive experiments on the GLUE benchmark, we demonstrate that TLoRA achieves
comparable performance to existing low-rank methods such as LoRA and
Adapter-based techniques, while requiring significantly fewer trainable
parameters. Analyzing the adaptation dynamics, we observe that TLoRA exhibits
Gaussian-like weight distributions, stable parameter norms, and scaling factor
variability across layers, further highlighting its expressive power and
adaptability. Additionally, we show that TLoRA closely resembles LoRA in its
eigenvalue distributions, parameter norms, and cosine similarity of updates,
underscoring its ability to effectively approximate LoRA's adaptation behavior.
Our results establish TLoRA as a highly efficient and effective fine-tuning
method for LLMs, offering a significant step forward in resource-efficient
model adaptation.
