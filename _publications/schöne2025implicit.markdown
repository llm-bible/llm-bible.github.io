---
layout: publication
title: 'Implicit Language Models Are Rnns: Balancing Parallelization And Expressivity'
authors: Mark Schöne, Babak Rahmani, Heiner Kremer, Fabian Falck, Hitesh Ballani, Jannes Gladrow
conference: "Arxiv"
year: 2025
bibkey: schöne2025implicit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07827"}
tags: ['Transformer', 'Language Modeling', 'Model Architecture', 'Large-Scale Training', 'Training Techniques', 'Pretraining Methods']
---
State-space models (SSMs) and transformers dominate the language modeling
landscape. However, they are constrained to a lower computational complexity
than classical recurrent neural networks (RNNs), limiting their expressivity.
In contrast, RNNs lack parallelization during training, raising fundamental
questions about the trade off between parallelization and expressivity. We
propose implicit SSMs, which iterate a transformation until convergence to a
fixed point. Theoretically, we show that implicit SSMs implement the non-linear
state-transitions of RNNs. Empirically, we find that only approximate
fixed-point convergence suffices, enabling the design of a scalable training
curriculum that largely retains parallelization, with full convergence required
only for a small subset of tokens. Our approach demonstrates superior
state-tracking capabilities on regular languages, surpassing transformers and
SSMs. We further scale implicit SSMs to natural language reasoning tasks and
pretraining of large-scale language models up to 1.3B parameters on 207B tokens
- representing, to our knowledge, the largest implicit model trained to date.
Notably, our implicit models outperform their explicit counterparts on standard
benchmarks.
