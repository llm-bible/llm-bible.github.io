---
layout: publication
title: 'Accelerating Natural Language Understanding In Task-oriented Dialog'
authors: Ojas Ahuja, Shrey Desai
conference: "Arxiv"
year: 2020
bibkey: ahuja2020accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2006.03701"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pruning', 'Pretraining Methods', 'BERT', 'Transformer', 'Applications']
---
Task-oriented dialog models typically leverage complex neural architectures
and large-scale, pre-trained Transformers to achieve state-of-the-art
performance on popular natural language understanding benchmarks. However,
these models frequently have in excess of tens of millions of parameters,
making them impossible to deploy on-device where resource-efficiency is a major
concern. In this work, we show that a simple convolutional model compressed
with structured pruning achieves largely comparable results to BERT on ATIS and
Snips, with under 100K parameters. Moreover, we perform acceleration
experiments on CPUs, where we observe our multi-task model predicts intents and
slots nearly 63x faster than even DistilBERT.
