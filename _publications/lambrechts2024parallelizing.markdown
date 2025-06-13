---
layout: publication
title: 'Parallelizing Autoregressive Generation With Variational State Space Models'
authors: Gaspard Lambrechts, Yann Claes, Pierre Geurts, Damien Ernst
conference: "ICML Workshop on Next Generation of Sequence Modeling Architectures 2024"
year: 2024
bibkey: lambrechts2024parallelizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08415"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Attention-based models such as Transformers and recurrent models like state
space models (SSMs) have emerged as successful methods for autoregressive
sequence modeling. Although both enable parallel training, none enable parallel
generation due to their autoregressiveness. We propose the variational SSM
(VSSM), a variational autoencoder (VAE) where both the encoder and decoder are
SSMs. Since sampling the latent variables and decoding them with the SSM can be
parallelized, both training and generation can be conducted in parallel.
Moreover, the decoder recurrence allows generation to be resumed without
reprocessing the whole sequence. Finally, we propose the autoregressive VSSM
that can be conditioned on a partial realization of the sequence, as is common
in language generation tasks. Interestingly, the autoregressive VSSM still
enables parallel generation. We highlight on toy problems (MNIST, CIFAR) the
empirical gains in speed-up and show that it competes with traditional models
in terms of generation quality (Transformer, Mamba SSM).
