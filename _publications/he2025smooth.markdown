---
layout: publication
title: 'Treekv: Smooth Key-value Cache Compression With Tree Structures'
authors: Ziwei He, Jian Yuan, Haoli Bai, Jingwen Leng, Bo Jiang
conference: "Arxiv"
year: 2025
bibkey: he2025smooth
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04987"}
tags: ['Transformer', 'Efficiency and Optimization', 'Ethics and Bias', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Efficient key-value (KV) cache compression is critical for scaling transformer-based Large Language Models (LLMs) in long sequences and resource-limited settings. Existing methods evict tokens based on their positions or importance scores, but position-based strategies can miss crucial information outside predefined regions, while those relying on global importance scores resulting in strong regional biases, limiting the KV cache's overall context retention and potentially impairing the performance of LLMs on complex tasks. Our wavelet analysis reveals that as tokens approach the end of sequence, their contributions to generation gradually increase and tends to diverge more from neighboring tokens, indicating a smooth transition with increasing complexity and variability from distant to nearby context. Motivated by this observation, we propose TreeKV, an intuitive, training-free method that employs a tree structure for smooth cache compression. TreeKV maintains a fixed cache size, allowing LLMs to deliver high-quality output even in long text scenarios. Unlike most compression methods, TreeKV is applicable to both the generation and prefilling stages. TreeKV consistently surpasses all baseline models in language modeling tasks on PG19 and OpenWebText2, allowing LLMs trained with short context window to generalize to longer window with a 16x cache reduction. On the Longbench benchmark, TreeKV achieves the best performance with only 6% of the budget at optimal efficiency.
