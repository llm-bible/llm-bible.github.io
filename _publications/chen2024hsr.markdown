---
layout: publication
title: 'Hsr-enhanced Sparse Attention Acceleration'
authors: Bo Chen, Yingyu Liang, Zhizhou Sha, Zhenmei Shi, Zhao Song
conference: "Arxiv"
year: 2024
bibkey: chen2024hsr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10165"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Prompting']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities across
various applications, but their performance on long-context tasks is often
limited by the computational complexity of attention mechanisms. We introduce a
novel approach to accelerate attention computation in LLMs, particularly for
long-context scenarios. We leverage the inherent sparsity within attention
mechanisms, both in conventional Softmax attention and ReLU attention (with
\\(\mathsf\{ReLU\}^\alpha\\) activation, \\(\alpha \in \mathbb\{N\}_+\\)), to significantly
reduce the running time complexity. Our method employs a Half-Space Reporting
(HSR) data structure to identify non-zero or ``massively activated'' entries in
the attention matrix. We present theoretical analyses for two key scenarios:
generation decoding and prompt prefilling. Our approach achieves a running time
of \\(O(mn^\{4/5\})\\) significantly faster than the naive approach \\(O(mn)\\) for
generation decoding, where \\(n\\) is the context length, \\(m\\) is the query length,
and \\(d\\) is the hidden dimension. We can also reduce the running time for prompt
prefilling from \\(O(mn)\\) to \\(O(mn^\{1 - 1 / \lfloor d/2\rfloor\} + mn^\{4/5\})\\). Our
method introduces only provably negligible error for Softmax attention. This
work represents a significant step towards enabling efficient long-context
processing in LLMs.
