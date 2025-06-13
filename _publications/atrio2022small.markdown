---
layout: publication
title: 'Small Batch Sizes Improve Training Of Low-resource Neural MT'
authors: Àlex R. Atrio, Andrei Popescu-belis
conference: "Arxiv"
year: 2022
bibkey: atrio2022small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.10579"}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
We study the role of an essential hyper-parameter that governs the training
of Transformers for neural machine translation in a low-resource setting: the
batch size. Using theoretical insights and experimental evidence, we argue
against the widespread belief that batch size should be set as large as allowed
by the memory of the GPUs. We show that in a low-resource setting, a smaller
batch size leads to higher scores in a shorter training time, and argue that
this is due to better regularization of the gradients during training.
