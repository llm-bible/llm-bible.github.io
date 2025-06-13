---
layout: publication
title: 'Efficient Llama-3.2-vision By Trimming Cross-attended Visual Features'
authors: Jewon Lee, Ki-ung Song, Seungmin Yang, Donguk Lim, Jaeyeon Kim, Wooksu Shin, Bo-kyeong Kim, Yong Jae Lee, Tae-ho Kim
conference: "Arxiv"
year: 2025
bibkey: lee2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00557'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Multimodal Models']
---
Visual token reduction lowers inference costs caused by extensive image
features in large vision-language models (LVLMs). Unlike relevant studies that
prune tokens in self-attention-only LVLMs, our work uniquely addresses
cross-attention-based models, which achieve superior performance. We identify
that the key-value (KV) cache size for image tokens in cross-attention layers
significantly exceeds that of text tokens in self-attention layers, posing a
major compute bottleneck. To mitigate this issue, we exploit the sparse nature
in cross-attention maps to selectively prune redundant visual features. Our
Trimmed Llama effectively reduces KV cache demands without requiring additional
training. By benefiting from 50%-reduced visual features, our model can reduce
inference latency and memory usage while achieving benchmark parity.
