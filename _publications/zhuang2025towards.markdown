---
layout: publication
title: 'Towards Better Instruction Following Retrieval Models'
authors: Yuchen Zhuang, Aaron Trinh, Rushi Qiang, Haotian Sun, Chao Zhang, Hanjun Dai, Bo Dai
conference: "Arxiv"
year: 2025
bibkey: zhuang2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21439'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Modern information retrieval (IR) models, trained exclusively on standard <query, passage> pairs, struggle to effectively interpret and follow explicit user instructions. We introduce InF-IR, a large-scale, high-quality training corpus tailored for enhancing retrieval models in Instruction-Following IR. InF-IR expands traditional training pairs into over 38,000 expressive <instruction, query, passage> triplets as positive samples. In particular, for each positive triplet, we generate two additional hard negative examples by poisoning both instructions and queries, then rigorously validated by an advanced reasoning model (o3-mini) to ensure semantic plausibility while maintaining instructional incorrectness. Unlike existing corpora that primarily support computationally intensive reranking tasks for decoder-only language models, the highly contrastive positive-negative triplets in InF-IR further enable efficient representation learning for smaller encoder-only models, facilitating direct embedding-based retrieval. Using this corpus, we train InF-Embed, an instruction-aware Embedding model optimized through contrastive learning and instruction-query attention mechanisms to align retrieval outcomes precisely with user intents. Extensive experiments across five instruction-based retrieval benchmarks demonstrate that InF-Embed significantly surpasses competitive baselines by 8.1% in p-MRR, measuring the instruction-following capabilities.
