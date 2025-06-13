---
layout: publication
title: 'Batch-max: Higher LLM Throughput Using Larger Batch Sizes And KV Cache Compression'
authors: Michael R. Metel, Boxing Chen, Mehdi Rezagholizadeh
conference: "Arxiv"
year: 2024
bibkey: metel2024batch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05693"}
tags: ['Prompting']
---
Several works have developed eviction policies to remove key-value (KV) pairs
from the KV cache for more efficient inference. The focus has been on
compressing the KV cache after the input prompt has been processed for faster
token generation. In settings with limited GPU memory, and when the input
context is longer than the generation length, we show that by also compressing
the KV cache during the input processing phase, larger batch sizes can be used
resulting in significantly higher throughput while still maintaining the
original model's accuracy.
