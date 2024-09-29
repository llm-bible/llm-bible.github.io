---
layout: publication
title: "Wkvquant: Quantizing Weight And Key/value Cache For Large Language Models Gains More"
authors: Yue Yuxuan, Yuan Zhihang, Duanmu Haojie, Zhou Sifan, Wu Jianlong, Nie Liqiang
conference: "Arxiv"
year: 2024
bibkey: yue2024quantizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12065"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Quantization', 'Tools']
---
Large Language Models (LLMs) face significant deployment challenges due to their substantial memory requirements and the computational demands of auto-regressive text generation process. This paper addresses these challenges by focusing on the quantization of LLMs a technique that reduces memory consumption by converting model parameters and activations into low-bit integers. We critically analyze the existing quantization approaches identifying their limitations in balancing the accuracy and efficiency of the quantized LLMs. To advance beyond these limitations we propose WKVQuant a PTQ framework especially designed for quantizing weights and the key/value (KV) cache of LLMs. Specifically we incorporates past-only quantization to improve the computation of attention. Additionally we introduce two-dimensional quantization strategy to handle the distribution of KV cache along with a cross-block reconstruction regularization for parameter optimization. Experiments show that WKVQuant achieves almost comparable memory savings to weight-activation quantization while also approaching the performance of weight-only quantization.
