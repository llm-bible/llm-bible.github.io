---
layout: publication
title: ABQ45;LLM Arbitrary45;bit Quantized Inference Acceleration For Large Language Models
authors: Zeng Chao, Liu Songwei, Xie Yusheng, Liu Hong, Wang Xiaojian, Wei Miao, Yang Shu, Chen Fangmin, Mei Xing
conference: "Arxiv"
year: 2024
bibkey: zeng2024abq
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08554"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs) have revolutionized natural language processing tasks. However their practical application is constrained by substantial memory and computational demands. Post45;training quantization (PTQ) is considered an effective method to accelerate LLM inference. Despite its growing popularity in LLM model compression PTQ deployment faces two major challenges. First low45;bit quantization leads to performance degradation. Second restricted by the limited integer computing unit type on GPUs quantized matrix operations with different precisions cannot be effectively accelerated. To address these issues we introduce a novel arbitrary45;bit quantization algorithm and inference framework ABQ45;LLM. It achieves superior performance across various quantization settings and enables efficient arbitrary45;precision quantized inference on the GPU. ABQ45;LLM introduces several key innovations (1) a distribution correction method for transformer blocks to mitigate distribution differences caused by full quantization of weights and activations improving performance at low bit45;widths. (2) the bit balance strategy to counteract performance degradation from asymmetric distribution issues at very low bit45;widths (e.g. 245;bit). (3) an innovative quantization acceleration framework that reconstructs the quantization matrix multiplication of arbitrary precision combinations based on BTC (Binary TensorCore) equivalents gets rid of the limitations of INT4/INT8 computing units. ABQ45;LLM can convert each component bit width gain into actual acceleration gain maximizing performance under mixed precision(e.g. W6A6 W2A8). Based on W2A8 quantization configuration on LLaMA45;7B model it achieved a WikiText2 perplexity of 7.59 (2.17downarrow vs 9.76 in AffineQuant). Compared to SmoothQuant we realized 1.6× acceleration improvement and 2.7× memory compression gain.
