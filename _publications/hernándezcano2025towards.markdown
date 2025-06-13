---
layout: publication
title: 'Towards Fully FP8 GEMM LLM Training At Scale'
authors: Alejandro Hernández-cano, Dhia Garbaya, Imanol Schlag, Martin Jaggi
conference: "Arxiv"
year: 2025
bibkey: hernándezcano2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20524"}
tags: ['Transformer', 'Pre-Training', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Despite the significant potential of FP8 data formats for large language model (LLM) pre-training, their adoption has been limited due to challenges in maintaining stability at scale. Existing approaches often rely on suboptimal fine-grained FP8 kernels or fall back to higher-precision matrix multiplications (GEMMs) in sensitive components, such as attention projections, compromising potential throughput gains. We introduce a new class of LLM architectures that, for the first time, support FP8 computation for all GEMMs within transformer blocks during both forward and backward passes. This enables unprecedented throughput gains, particularly at scale, while matching the downstream performance of standard BF16 training. Our architecture design reduces large outlier activations, promoting stable long-term FP8 training. In addition, we identify key metrics to monitor low-precision training and predict potential future divergences.
