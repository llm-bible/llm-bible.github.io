---
layout: publication
title: 'Int-flashattention: Enabling Flash Attention For INT8 Quantization'
authors: Shimao Chen, Zirui Liu, Zhiying Wu, Ce Zheng, Peizhuang Cong, Zihan Jiang, Yuhan Wu, Lei Su, Tong Yang
conference: "Arxiv"
year: 2024
bibkey: chen2024int
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.16997"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Quantization']
---
As the foundation of large language models (LLMs), self-attention module
faces the challenge of quadratic time and memory complexity with respect to
sequence length. FlashAttention accelerates attention computation and reduces
its memory usage by leveraging the GPU memory hierarchy. A promising research
direction is to integrate FlashAttention with quantization methods. This paper
introduces INT-FlashAttention, the first INT8 quantization architecture
compatible with the forward workflow of FlashAttention, which significantly
improves the inference speed of FlashAttention on Ampere GPUs. We implement our
INT-FlashAttention prototype with fully INT8 activations and general
matrix-multiplication (GEMM) kernels, making it the first attention operator
with fully INT8 input. As a general token-level post-training quantization
framework, INT-FlashAttention is also compatible with other data formats like
INT4, etc. Experimental results show INT-FlashAttention achieves 72% faster
inference speed and 82% smaller quantization error compared to standard
FlashAttention with FP16 and FP8 data format.
