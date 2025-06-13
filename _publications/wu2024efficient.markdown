---
layout: publication
title: 'Tokenselect: Efficient Long-context Inference And Length Extrapolation For Llms Via Dynamic Token-level KV Cache Selection'
authors: Wei Wu, Zhuoshi Pan, Chao Wang, Liyi Chen, Yunchu Bai, Tianfu Wang, Kun Fu, Zheng Wang, Hui Xiong
conference: "Arxiv"
year: 2024
bibkey: wu2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02886'}
tags: ['Attention Mechanism', 'Training Techniques', 'Tools', 'Applications', 'Model Architecture']
---
The rapid advancement of Large Language Models (LLMs) has driven growing
demand for processing extended context sequences in contemporary applications.
However, this progress faces two major challenges: performance degradation due
to sequence lengths out-of-distribution, and excessively long inference times
caused by the quadratic computational complexity of attention. These issues
hinder the application of LLMs in long-context scenarios. In this paper, we
propose Dynamic Token-Level KV Cache Selection (TokenSelect), a training-free
method for efficient and accurate long-context inference. TokenSelect builds
upon the observation of non-contiguous attention sparsity, using Query-Key dot
products to measure per-head KV Cache criticality at token-level. By per-head
soft voting mechanism, TokenSelect selectively involves a few critical KV cache
tokens in attention calculation without sacrificing accuracy. To further
accelerate TokenSelect, we design the Selection Cache based on observations of
consecutive Query similarity and implemented efficient dot product kernel,
significantly reducing the overhead. A comprehensive evaluation of TokenSelect
demonstrates up to 23.84x speedup in attention computation and up to 2.28x
acceleration in end-to-end latency, while providing superior performance
compared to state-of-the-art long-context inference methods.
