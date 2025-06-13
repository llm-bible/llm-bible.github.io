---
layout: publication
title: 'Video-xl-pro: Reconstructive Token Compression For Extremely Long Video Understanding'
authors: Xiangrui Liu, Yan Shu, Zheng Liu, Ao Li, Yang Tian, Bo Zhao
conference: "Arxiv"
year: 2025
bibkey: liu2025video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18478"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Pruning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Despite advanced token compression techniques, existing multimodal large
language models (MLLMs) still struggle with hour-long video understanding. In
this work, we propose Video-XL-Pro, an efficient method for extremely long
video understanding, built upon Reconstructive Compression of Tokens (ReCoT), a
learnable module that leverages self-supervised learning to generate
comprehensive and compact video tokens. ReCoT introduces two key components:
(i) Dynamic Token Synthesizer (DTS): DTS generates pseudo-video tokens from
static image tokens by learning intra-token relationships, which are then used
in masked video modeling. (ii) Semantic-Guided Masking (SGM): SGM adaptively
masks redundant visual tokens to facilitate more effective reconstructive
learning. To improve training efficiency in MLLMs fine-tuning, we introduce a
video-specific dataset pruning strategy and design a simple yet Query-aware
Selector that enables the model to precisely locate query-relevant video
tokens. With only 3B parameters, Video-XL-Pro outperforms most 7B models
trained on larger datasets across multiple long video understanding benchmarks.
Moreover, it can process over 8K frames on a single A100 GPU while maintaining
high-quality performance.
