---
layout: publication
title: 'LLM Vocabulary Compression For Low-compute Environments'
authors: Sreeram Vennam, Anish Joishy, Ponnurangam Kumaraguru
conference: "Arxiv"
year: 2024
bibkey: vennam2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06371"}
tags: ['GPT', 'Model Architecture']
---
We present a method to compress the final linear layer of language models,
reducing memory usage by up to 3.4x without significant performance loss. By
grouping tokens based on Byte Pair Encoding (BPE) merges, we prevent
materialization of the memory-intensive logits tensor. Evaluations on the
TinyStories dataset show that our method performs on par with GPT-Neo and GPT2
while significantly improving throughput by up to 3x, making it suitable for
low-compute environments.
