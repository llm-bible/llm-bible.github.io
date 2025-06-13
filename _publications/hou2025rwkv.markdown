---
layout: publication
title: 'RWKV-X: A Linear Complexity Hybrid Language Model'
authors: Haowen Hou, Zhiyi Huang, Kaifeng Tan, Rongchang Lu, Fei Richard Yu
conference: "Arxiv"
year: 2025
bibkey: hou2025rwkv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.21463"}
  - {name: "Code", url: "https://github.com/howard-hou/RWKV-X"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'Transformer', 'Has Code', 'Attention Mechanism']
---
In this paper, we introduce RWKV-X, a novel hybrid architecture that combines the efficiency of RWKV for short-range modeling with a sparse attention mechanism designed to capture long-range context. Unlike previous hybrid approaches that rely on full attention layers and retain quadratic complexity, RWKV-X achieves linear-time complexity in training and constant-time complexity in inference decoding. We demonstrate that RWKV-X, when continually pretrained on 64K-token sequences, achieves near-perfect accuracy on the 64K passkey retrieval benchmark. It consistently outperforms prior RWKV-7 models on long-context benchmarks, while maintaining strong performance on short-context tasks. These results highlight RWKV-X as a scalable and efficient backbone for general-purpose language modeling, capable of decoding sequences up to 1 million tokens with stable speed and memory usage. To facilitate further research and analysis, we have made the checkpoints and the associated code publicly accessible at: https://github.com/howard-hou/RWKV-X.
