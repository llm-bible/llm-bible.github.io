---
layout: publication
title: 'LOCOST: State-space Models For Long Document Abstractive Summarization'
authors: Florian Le Bronnec, Song Duong, Mathieu Ravaut, Alexandre Allauzen, Nancy F. Chen, Vincent Guigue, Alberto Lumbreras, Laure Soulier, Patrick Gallinari
conference: "Arxiv"
year: 2024
bibkey: bronnec2024state
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17919"}
tags: ['Transformer', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
State-space models are a low-complexity alternative to transformers for
encoding long sequences and capturing long-term dependencies. We propose
LOCOST: an encoder-decoder architecture based on state-space models for
conditional text generation with long context inputs. With a computational
complexity of \\(O(L log L)\\), this architecture can handle significantly longer
sequences than state-of-the-art models that are based on sparse attention
patterns. We evaluate our model on a series of long document abstractive
summarization tasks. The model reaches a performance level that is 93-96%
comparable to the top-performing sparse transformers of the same size while
saving up to 50% memory during training and up to 87% during inference.
Additionally, LOCOST effectively handles input texts exceeding 600K tokens at
inference time, setting new state-of-the-art results on full-book summarization
and opening new perspectives for long input processing.
