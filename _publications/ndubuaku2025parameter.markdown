---
layout: publication
title: 'Parameter-efficient Transformer Embeddings'
authors: Henry Ndubuaku, Mouad Talhi
conference: "Arxiv"
year: 2025
bibkey: ndubuaku2025parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.02266"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer']
---
Embedding layers in transformer-based NLP models typically account for the
largest share of model parameters, scaling with vocabulary size but not
yielding performance gains proportional to scale. We propose an alternative
approach in which token embedding vectors are first generated
deterministically, directly from the token IDs using a Fourier expansion of
their normalized values, followed by a lightweight multilayer perceptron (MLP)
that captures higher-order interactions. We train standard transformers and our
architecture on natural language inference tasks (SNLI and MNLI), and evaluate
zero-shot performance on sentence textual similarity (STS-B). Our results
demonstrate that the proposed method achieves competitive performance using
significantly fewer parameters, trains faster, and operates effectively without
the need for dropout. This proof-of-concept study highlights the potential for
scalable, memory-efficient language models and motivates further large-scale
experimentation based on our findings.
