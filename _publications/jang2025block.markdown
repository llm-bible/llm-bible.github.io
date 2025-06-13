---
layout: publication
title: 'Blockdialect: Block-wise Fine-grained Mixed Format Quantization For Energy-efficient LLM Inference'
authors: Wonsuk Jang, Thierry Tambe
conference: "Arxiv"
year: 2025
bibkey: jang2025block
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.01144'}
tags: ['RAG', 'Efficiency and Optimization', 'Tools', 'Quantization', 'Merging', 'Reinforcement Learning']
---
The rapidly increasing size of large language models (LLMs) presents
significant challenges in memory usage and computational costs. Quantizing both
weights and activations can address these issues, with hardware-supported
fine-grained scaling emerging as a promising solution to mitigate outliers.
However, existing methods struggle to capture nuanced block data distributions.
We propose BlockDialect, a block-wise fine-grained mixed format technique that
assigns a per-block optimal number format from a formatbook for better data
representation. Additionally, we introduce DialectFP4, a formatbook of FP4
variants (akin to dialects) that adapt to diverse data distributions. To
leverage this efficiently, we propose a two-stage approach for online
DialectFP4 activation quantization. Importantly, DialectFP4 ensures energy
efficiency by selecting representable values as scaled integers compatible with
low-precision integer arithmetic. BlockDialect achieves 10.78% (7.48%) accuracy
gain on the LLaMA3-8B (LLaMA2-7B) model compared to MXFP4 format with lower bit
usage per data, while being only 5.45% (2.69%) below full precision even when
quantizing full-path matrix multiplication. Focusing on how to represent over
how to scale, our work presents a promising path for energy-efficient LLM
inference.
