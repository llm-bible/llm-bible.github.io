---
layout: publication
title: 'Mquant: Unleashing The Inference Potential Of Multimodal Large Language Models Via Full Static Quantization'
authors: Jiangyong Yu, Sifan Zhou, Dawei Yang, Shuo Wang, Shuoyu Li, Xing Hu, Chen Xu, Zukang Xu, Changyong Shu, Zhihang Yuan
conference: "Arxiv"
year: 2025
bibkey: yu2025unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00425"}
tags: ['Tools', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models', 'Quantization']
---
Multimodal large language models (MLLMs) have garnered widespread attention
due to their ability to understand multimodal input. However, their large
parameter sizes and substantial computational demands severely hinder their
practical deployment and application.While quantization is an effective way to
reduce model size and inference latency, its application to MLLMs remains
underexplored. In this paper, we propose MQuant, a post-training quantization
(PTQ) framework designed to tackle the unique challenges of multimodal large
language models (MLLMs). Conventional quantization often struggles with MLLMs
because of (a) high inference latency from large visual token counts, (b)
distributional disparities between visual and textual tokens, and (c) extreme
outliers introduced by Hadamard-based transformations. To address these issues,
MQuant introduces: Modality-Specific Static Quantization (MSQ), assigning
distinct static scales for visual vs. textual tokens; Attention-Invariant
Flexible Switching (AIFS), reordering tokens to preserve casual attention while
eliminating expensive token-wise scale computations; Rotation Magnitude
Suppression (RMS), mitigating weight outliers arising from online Hadamard
rotations. On five mainstream MLLMs (including Qwen-VL, MiniCPM-V, CogVLM2),
MQuant under W4A8 achieves near-floating-point accuracy (<1% degradation) while
reducing inference latency by up to 30%, significantly outperforming existing
PTQ baselines. Our MQuant effectively bridges the gap for efficient and
accurate MLLMs inference in resource-constrained devices. Code will be
released.
