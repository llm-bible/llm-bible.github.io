---
layout: publication
title: 'SALE : Low-bit Estimation For Efficient Sparse Attention In Long-context LLM Prefilling'
authors: Xiaodong Ji, Hailin Zhang, Fangcheng Fu, Bin Cui
conference: "Arxiv"
year: 2025
bibkey: ji2025sale
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24179"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism']
---
Many advanced Large Language Model (LLM) applications require long-context processing, but the self-attention module becomes a bottleneck during the prefilling stage of inference due to its quadratic time complexity with respect to sequence length. Existing sparse attention methods accelerate attention computation by skipping less significant regions of the attention map. However, these approaches typically perform coarse-grained inspection of the attention map, rendering considerable loss in model accuracy. In this paper, we propose SALE, a fine-grained sparse attention method that accelerates the long-context prefilling stage of LLM with negligible loss in model accuracy. SALE achieves fast and accurate fine-grained attention weight estimation through 4-bit quantized query-key products, followed by block-sparse attention to accelerate prefilling computations. For importance evaluation for query-key pairs, we adopt our Relative Attention Score metric, which offers significantly higher efficiency within our framework. We implement a custom CUDA kernel optimized for our approach for hardware efficiency, reducing the additional overhead to approximately 11% of the full attention latency. Notably, SALE requires no parameter training and can be seamlessly integrated into existing systems with trivial code modifications. Experiments on long-context benchmarks demonstrate that our method outperforms existing approaches in accuracy-efficiency trade-offs, achieving at least 3.36x speedups on Llama-3.1-8B for sequences longer than 64K while maintaining model quality.
