---
layout: publication
title: 'LUT Tensor Core: A Software-hardware Co-design For Lut-based Low-bit LLM Inference'
authors: Zhiwen Mo, Lei Wang, Jianyu Wei, Zhichen Zeng, Shijie Cao, Lingxiao Ma, Naifeng Jing, Ting Cao, Jilong Xue, Fan Yang, Mao Yang
conference: "Arxiv"
year: 2024
bibkey: mo2024lut
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.06003'}
tags: ['RAG', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Quantization', 'Merging', 'Applications', 'Reinforcement Learning']
---
As large language model (LLM) inference continues to demand increasing computational resources, there is a rapidly growing trend toward using low-bit weights to reduce memory footprint and improve inference efficiency. However, low-bit LLMs introduce the need for mixed-precision general matrix multiplication (mpGEMM), which involves multiplying low-precision weights with higher-precision activations - a critical yet under-explored operation. Current hardware lacks native support for mpGEMM, leading to inefficient dequantization-based implementations.
  To address this, we explore a lookup table (LUT)-based approach to accelerate mpGEMM. While conventional LUT implementations fall short in performance and flexibility, we propose LUT Tensor Core, a software-hardware co-designed solution optimized for low-bit LLM inference. On the software side, we introduce operator fusion and table symmetrization techniques to optimize LUT generation and storage. On the hardware side, LUT Tensor Core adopts an elongated tiling shape to maximize table reuse and employs a bit-serial architecture to flexibly support a variety of precision combinations. Additionally, we design an end-to-end compilation stack with custom instructions to enable efficient code generation and optimization for LUT-based mpGEMM. Experimental results on low-bit LLMs such as BitNet and LLaMA demonstrate that LUT Tensor Core delivers over an order-of-magnitude improvement in both compute density and energy efficiency.
