---
layout: publication
title: 'ABQ-LLM: Arbitrary-bit Quantized Inference Acceleration For Large Language Models'
authors: Chao Zeng, Songwei Liu, Yusheng Xie, Hong Liu, Xiaojian Wang, Miao Wei, Shu Yang, Fangmin Chen, Xing Mei
conference: "Arxiv"
year: 2024
bibkey: zeng2024abq
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08554"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
Large Language Models (LLMs) have revolutionized natural language processing
tasks. However, their practical application is constrained by substantial
memory and computational demands. Post-training quantization (PTQ) is
considered an effective method to accelerate LLM inference. Despite its growing
popularity in LLM model compression, PTQ deployment faces two major challenges.
First, low-bit quantization leads to performance degradation. Second,
restricted by the limited integer computing unit type on GPUs, quantized matrix
operations with different precisions cannot be effectively accelerated. To
address these issues, we introduce a novel arbitrary-bit quantization algorithm
and inference framework, ABQ-LLM. It achieves superior performance across
various quantization settings and enables efficient arbitrary-precision
quantized inference on the GPU. ABQ-LLM introduces several key innovations: (1)
a distribution correction method for transformer blocks to mitigate
distribution differences caused by full quantization of weights and
activations, improving performance at low bit-widths. (2) the bit balance
strategy to counteract performance degradation from asymmetric distribution
issues at very low bit-widths (e.g., 2-bit). (3) an innovative quantization
acceleration framework that reconstructs the quantization matrix multiplication
of arbitrary precision combinations based on BTC (Binary TensorCore)
equivalents, gets rid of the limitations of INT4/INT8 computing units. ABQ-LLM
can convert each component bit width gain into actual acceleration gain,
maximizing performance under mixed precision(e.g., W6A6, W2A8). Based on W2*A8
quantization configuration on LLaMA-7B model, it achieved a WikiText2
perplexity of 7.59 (2.17\\(\downarrow \\) vs 9.76 in AffineQuant). Compared to
SmoothQuant, we realized 1.6\\(\times\\) acceleration improvement and 2.7\\(\times\\)
memory compression gain.
