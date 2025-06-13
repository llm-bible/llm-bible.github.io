---
layout: publication
title: 'Hitvideo: Hierarchical Tokenizers For Enhancing Text-to-video Generation With Autoregressive Large Language Models'
authors: Ziqin Zhou, Yifan Yang, Yuqing Yang, Tianyu He, Houwen Peng, Kai Qiu, Qi Dai, Lili Qiu, Chong Luo, Lingqiao Liu
conference: "Arxiv"
year: 2025
bibkey: zhou2025hierarchical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.11513'}
  - {name: "Code", url: 'https://ziqinzhou66.github.io/project/HiTVideo'}
tags: ['Has Code', 'Efficiency and Optimization', 'GPT', 'Tools', 'Pretraining Methods']
---
Text-to-video generation poses significant challenges due to the inherent
complexity of video data, which spans both temporal and spatial dimensions. It
introduces additional redundancy, abrupt variations, and a domain gap between
language and vision tokens while generation. Addressing these challenges
requires an effective video tokenizer that can efficiently encode video data
while preserving essential semantic and spatiotemporal information, serving as
a critical bridge between text and vision. Inspired by the observation in
VQ-VAE-2 and workflows of traditional animation, we propose HiTVideo for
text-to-video generation with hierarchical tokenizers. It utilizes a 3D causal
VAE with a multi-layer discrete token framework, encoding video content into
hierarchically structured codebooks. Higher layers capture semantic information
with higher compression, while lower layers focus on fine-grained
spatiotemporal details, striking a balance between compression efficiency and
reconstruction quality. Our approach efficiently encodes longer video sequences
(e.g., 8 seconds, 64 frames), reducing bits per pixel (bpp) by approximately
70% compared to baseline tokenizers, while maintaining competitive
reconstruction quality. We explore the trade-offs between compression and
reconstruction, while emphasizing the advantages of high-compressed semantic
tokens in text-to-video tasks. HiTVideo aims to address the potential
limitations of existing video tokenizers in text-to-video generation tasks,
striving for higher compression ratios and simplify LLMs modeling under
language guidance, offering a scalable and promising framework for advancing
text to video generation. Demo page:
https://ziqinzhou66.github.io/project/HiTVideo.
