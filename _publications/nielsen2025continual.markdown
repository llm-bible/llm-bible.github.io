---
layout: publication
title: 'Continual Quantization-aware Pre-training: When To Transition From 16-bit To 1.58-bit Pre-training For Bitnet Language Models?'
authors: Jacob Nielsen, Peter Schneider-kamp, Lukas Galke
conference: "Arxiv"
year: 2025
bibkey: nielsen2025continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11895"}
tags: ['Training Techniques', 'Pre-Training', 'Efficiency and Optimization', 'Quantization']
---
Large language models (LLMs) require immense resources for training and
inference. Quantization, a technique that reduces the precision of model
parameters, offers a promising solution for improving LLM efficiency and
sustainability. While post-training quantization methods typically achieve 4-8
bits per parameter, recent research suggests that training LLMs with 1.58 bits
per weight parameter from scratch can maintain model accuracy while greatly
reducing memory requirements and energy consumption at inference time. Here, we
investigate a training strategy for quantization-aware pre-training, where the
models are first trained with 16-bit precision and then transition into
1.58-bit quantization-aware training. Our results on 11 downstream tasks show
that this 16-to-1.58-bit training strategy is preferable over full 1.58-bit
training and leaves models closer to those which have undergone 16-bit
training. We further investigate the effects of retaining the optimizer state
at the transition point and gradually phasing in quantization strength --
finding that both techniques alleviate the magnitude of loss spikes, but also
that these effects can be compensated through further training.
