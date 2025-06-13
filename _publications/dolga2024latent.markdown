---
layout: publication
title: 'Latte: Latent Attention For Linear Time Transformers'
authors: Rares Dolga, Lucas Maystre, Marius Cobzarenco, David Barber
conference: "Arxiv"
year: 2024
bibkey: dolga2024latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17512"}
tags: ['Transformer', 'Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
The time complexity of the standard attention mechanism in transformers
scales quadratically with sequence length. We propose a probabilistic framework
for attention, enabling us to derive a novel low-rank linear
re-parameterisation of both bidirectional and causal cases, based on defining a
latent variable model. Our method can be seamlessly integrated as a drop-in
replacement for the standard attention mechanism. Additionally, this framework
provides a natural extension for combining local standard attention with our
global linear attention. This approach allows us to extend the context length
of existing large pre-trained models with only a few additional training steps.
The resulting ``Latte Transformer'' achieves performance comparable to standard
attention and other state-of-the-art models, while maintaining linear time and
memory complexity, along with constant-time next-token prediction during
inference.
