---
layout: publication
title: 'Attention Is All You Need But You Don''t Need All Of It For Inference Of Large Language Models'
authors: Georgy Tyukin, Gbetondji J-s Dovonon, Jean Kaddour, Pasquale Minervini
conference: "Arxiv"
year: 2024
bibkey: tyukin2024attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.15516'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture']
---
The inference demand for LLMs has skyrocketed in recent months, and serving
models with low latencies remains challenging due to the quadratic input length
complexity of the attention layers. In this work, we investigate the effect of
dropping MLP and attention layers at inference time on the performance of
Llama-v2 models. We find that dropping dreeper attention layers only marginally
decreases performance but leads to the best speedups alongside dropping entire
layers. For example, removing 33% of attention layers in a 13B Llama2 model
results in a 1.8% drop in average performance over the OpenLLM benchmark. We
also observe that skipping layers except the latter layers reduces performances
for more layers skipped, except for skipping the attention layers.
