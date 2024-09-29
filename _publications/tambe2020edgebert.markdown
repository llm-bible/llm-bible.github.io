---
layout: publication
title: EdgeBERT Sentence-Level Energy Optimizations for Latency-Aware Multi-Task NLP Inference
authors: Tambe Thierry, Hooper Coleman, Pentecost Lillian, Jia Tianyu, Yang En-yu, Donato Marco, Sanh Victor, Whatmough Paul N., Rush Alexander M., Brooks David, Wei Gu-yeon
conference: "Arxiv"
year: 2020
bibkey: tambe2020edgebert
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.14203"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Transformer-based language models such as BERT provide significant accuracy improvement for a multitude of natural language processing (NLP) tasks. However their hefty computational and memory demands make them challenging to deploy to resource-constrained edge platforms with strict latency requirements. We present EdgeBERT an in-depth algorithm-hardware co-design for latency-aware energy optimization for multi-task NLP. EdgeBERT employs entropy-based early exit predication in order to perform dynamic voltage-frequency scaling (DVFS) at a sentence granularity for minimal energy consumption while adhering to a prescribed target latency. Computation and memory footprint overheads are further alleviated by employing a calibrated combination of adaptive attention span selective network pruning and floating-point quantization. Furthermore in order to maximize the synergistic benefits of these algorithms in always-on and intermediate edge computing settings we specialize a 12nm scalable hardware accelerator system integrating a fast-switching low-dropout voltage regulator (LDO) an all-digital phase-locked loop (ADPLL) as well as high-density embedded non-volatile memories (eNVMs) wherein the sparse floating-point bit encodings of the shared multi-task parameters are carefully stored. Altogether latency-aware multi-task NLP inference acceleration on the EdgeBERT hardware system generates up to 7x 2.5x and 53x lower energy compared to the conventional inference without early stopping the latency-unbounded early exit approach and CUDA adaptations on an Nvidia Jetson Tegra X2 mobile GPU respectively.
