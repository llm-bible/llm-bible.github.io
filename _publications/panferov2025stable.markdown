---
layout: publication
title: 'Quest: Stable Training Of Llms With 1-bit Weights And Activations'
authors: Andrei Panferov, Jiale Chen, Soroush Tabesh, Roberto L. Castro, Mahdi Nikdan, Dan Alistarh
conference: "Arxiv"
year: 2025
bibkey: panferov2025stable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05003"}
  - {name: "Code", url: "https://github.com/IST-DASLab/QuEST"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques', 'Has Code', 'Scaling Laws', 'Quantization', 'Distillation', 'Arxiv']
---
One approach to reducing the massive costs of large language models (LLMs) is
the use of quantized or sparse representations for training or deployment.
While post-training compression methods are very popular, the question of
obtaining even more accurate compressed models by directly training over such
representations, i.e., Quantization-Aware Training (QAT), is still open: for
example, a recent study (arXiv:2411.04330v2) put the "optimal" bit-width at
which models can be trained using QAT, while staying accuracy-competitive with
standard FP16/BF16 precision, at 8-bits weights and activations.
  We advance this state-of-the-art via a new method called QuEST, which is
Pareto-competitive with FP16, i.e., it provides better accuracy at lower model
size, while training models with weights and activations in 4-bits or less.
Moreover, QuEST allows stable training with 1-bit weights and activations.
QuEST achieves this by improving two key aspects of QAT methods: (1) accurate
and fast quantization of the (continuous) distributions of weights and
activations via Hadamard normalization and MSE-optimal fitting; (2) a new trust
gradient estimator based on the idea of explicitly minimizing the error between
the noisy gradient computed over quantized states and the "true" (but unknown)
full-precision gradient. Experiments on Llama-type architectures show that
QuEST induces stable scaling laws across the entire range of hardware-supported
precisions, and can be extended to sparse representations. We provide GPU
kernel support showing that models produced by QuEST can be executed
efficiently. Our code is available at https://github.com/IST-DASLab/QuEST.
