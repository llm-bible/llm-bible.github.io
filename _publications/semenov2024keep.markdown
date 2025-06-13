---
layout: publication
title: 'Asterisk*: Keep It Simple'
authors: Andrew Semenov
conference: "Arxiv"
year: 2024
bibkey: semenov2024keep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05691"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Distillation', 'GPT', 'Applications', 'Attention Mechanism']
---
This paper describes Asterisk, a compact GPT-based model for generating text
embeddings. The model uses a minimalist architecture with two layers, two
attention heads, and 256 embedding dimensions. By applying knowledge
distillation from larger pretrained models, we explore the trade-offs between
model size and performance while minimizing computational and memory
requirements. The model is primarily evaluated and optimized for classification
tasks, with experimental results showing its moderate performance in zero-shot
classification across various downstream applications. With additional
configuration, the model performance can approach or even surpass that of
larger architectures on specific classification tasks.
