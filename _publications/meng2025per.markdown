---
layout: publication
title: 'PLPHP: Per-layer Per-head Vision Token Pruning For Efficient Large Vision-language Models'
authors: Yu Meng, Kaiyuan Li, Chenran Huang, Chen Gao, Xinlei Chen, Yong Li, Xiaoping Zhang
conference: "Arxiv"
year: 2025
bibkey: meng2025per
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14504'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Pruning', 'Multimodal Models']
---
Large Vision-Language Models (LVLMs) have demonstrated remarkable
capabilities across a range of multimodal tasks. However, their inference
efficiency is constrained by the large number of visual tokens processed during
decoding. To address this challenge, we propose Per-Layer Per-Head Vision Token
Pruning (PLPHP), a two-level fine-grained pruning method including Layer-Level
Retention Rate Allocation and Head-Level Vision Token Pruning. Motivated by the
Vision Token Re-attention phenomenon across decoder layers, we dynamically
adjust token retention rates layer by layer. Layers that exhibit stronger
attention to visual information preserve more vision tokens, while layers with
lower vision attention are aggressively pruned. Furthermore, PLPHP applies
pruning at the attention head level, enabling different heads within the same
layer to independently retain critical context. Experiments on multiple
benchmarks demonstrate that PLPHP delivers an 18% faster decoding speed and
reduces the Key-Value Cache (KV Cache) size by over 50%, all at the cost of
0.46% average performance drop, while also achieving notable performance
improvements in multi-image tasks. These results highlight the effectiveness of
fine-grained token pruning and contribute to advancing the efficiency and
scalability of LVLMs. Our source code will be made publicly available.
