---
layout: publication
title: 'Analog In-memory Computing Attention Mechanism For Fast And Energy-efficient Large Language Models'
authors: Nathan Leroux, Paul-philipp Manea, Chirag Sudarshan, Jan Finkbeiner, Sebastian Siegel, John Paul Strachan, Emre Neftci
conference: "Arxiv"
year: 2024
bibkey: leroux2024analog
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.19315'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Training Techniques', 'GPT', 'Merging', 'Pretraining Methods']
---
Transformer networks, driven by self-attention, are central to Large Language
Models. In generative Transformers, self-attention uses cache memory to store
token projections, avoiding recomputation at each time step. However,
GPU-stored projections must be loaded into SRAM for each new generation step,
causing latency and energy bottlenecks.
  We present a custom self-attention in-memory computing architecture based on
emerging charge-based memories called gain cells, which can be efficiently
written to store new tokens during sequence generation and enable parallel
analog dot-product computation required for self-attention. However, the analog
gain cell circuits introduce non-idealities and constraints preventing the
direct mapping of pre-trained models. To circumvent this problem, we design an
initialization algorithm achieving text processing performance comparable to
GPT-2 without training from scratch. Our architecture respectively reduces
attention latency and energy consumption by up to two and five orders of
magnitude compared to GPUs, marking a significant step toward ultra-fast,
low-power generative Transformers.
