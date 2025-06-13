---
layout: publication
title: 'Massive Values In Self-attention Modules Are The Key To Contextual Knowledge Understanding'
authors: Mingyu Jin, Kai Mei, Wujiang Xu, Mingjie Sun, Ruixiang Tang, Mengnan Du, Zirui Liu, Yongfeng Zhang
conference: "Arxiv"
year: 2025
bibkey: jin2025massive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01563"}
  - {name: "Code", url: "https://github.com/MingyuJ666/Rope_with_LLM"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Quantization']
---
Large language models (LLMs) have achieved remarkable success in contextual knowledge understanding. In this paper, we show that these concentrated massive values consistently emerge in specific regions of attention queries (Q) and keys (K) while not having such patterns in values (V) in various modern transformer-based LLMs (Q, K, and V mean the representations output by the query, key, and value layers respectively). Through extensive experiments, we further demonstrate that these massive values play a critical role in interpreting contextual knowledge (knowledge obtained from the current context window) rather than in retrieving parametric knowledge stored within the model's parameters. Our further investigation of quantization strategies reveals that ignoring these massive values leads to a pronounced drop in performance on tasks requiring rich contextual understanding, aligning with our analysis. Finally, we trace the emergence of concentrated massive values and find that such concentration is caused by Rotary Positional Encoding (RoPE), which has appeared since the first layers. These findings shed new light on how Q and K operate in LLMs and offer practical insights for model design and optimization. The Code is Available at https://github.com/MingyuJ666/Rope_with_LLM.
