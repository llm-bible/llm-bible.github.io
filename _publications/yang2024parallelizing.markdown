---
layout: publication
title: 'Parallelizing Linear Transformers With The Delta Rule Over Sequence Length'
authors: Yang Songlin, Wang Bailin, Zhang Yu, Shen Yikang, Kim Yoon
conference: "Arxiv"
year: 2024
bibkey: yang2024parallelizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06484"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Transformers with linear attention (i.e., linear transformers) and
state-space models have recently been suggested as a viable linear-time
alternative to transformers with softmax attention. However, these models still
underperform transformers especially on tasks that require in-context
retrieval. While more expressive variants of linear transformers which replace
the additive outer-product update in linear transformers with the delta rule
have been found to be more effective at associative recall, existing algorithms
for training such models do not parallelize over sequence length and are thus
inefficient to train on modern hardware. This work describes a
hardware-efficient algorithm for training linear transformers with the delta
rule, which exploits a memory-efficient representation for computing products
of Householder matrices. This algorithm allows us to scale up DeltaNet to
standard language modeling settings. We train a 1.3B model for 100B tokens and
find that it outperforms recent linear-time baselines such as Mamba and GLA in
terms of perplexity and zero-shot performance on downstream tasks (including on
tasks that focus on recall). We also experiment with two hybrid models which
combine DeltaNet layers with (1) sliding-window attention layers every other
layer or (2) two global attention layers, and find that these hybrid models
outperform strong transformer baselines.
