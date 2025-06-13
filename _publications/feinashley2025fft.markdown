---
layout: publication
title: 'SPECTRE: An Fft-based Efficient Drop-in Replacement To Self-attention For Long Contexts'
authors: Jacob Fein-ashley, Neelesh Gupta, Rajgopal Kannan, Viktor Prasanna
conference: "Arxiv"
year: 2025
bibkey: feinashley2025fft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18394"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Applications', 'Model Architecture', 'Language Modeling', 'Attention Mechanism', 'Pretraining Methods']
---
Long-context transformers face significant efficiency challenges due to the quadratic cost of self-attention. However, many modern applications-from multi-turn dialogue to high-resolution vision-require contexts spanning tens of thousands of tokens. We introduce SPECTRE, a method that replaces each attention head with a fast real FFT, a content-adaptive spectral gate, and an inverse FFT, reducing per-layer complexity from \\(\mathcal\{O\}(L^\{2\})\\) to \\(O(Llog L)\\) while preserving the surrounding architecture. We extend this efficiency to autoregressive generation through our Prefix-FFT cache and enhance local feature representation with an optional wavelet module that adds negligible computational overhead. Our experiments demonstrate that SPECTRE operates up to 7\\(\times\\) faster than FlashAttention-2 on 128k-token contexts while matching or exceeding baseline performance on PG-19 language modeling and ImageNet-1k classification tasks. SPECTRE achieves these improvements by adding fewer than 6% parameters to the base model, making hundred-kilotoken context processing feasible on commodity GPUs without specialized hardware.
