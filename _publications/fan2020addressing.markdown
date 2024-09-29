---
layout: publication
title: 'Addressing Some Limitations Of Transformers With Feedback Memory'
authors: Fan Angela, Lavril Thibaut, Grave Edouard, Joulin Armand, Sukhbaatar Sainbayar
conference: "Arxiv"
year: 2020
bibkey: fan2020addressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.09402"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Language Modeling', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Transformers have been successfully applied to sequential auto-regressive tasks despite being feedforward networks. Unlike recurrent neural networks Transformers use attention to capture temporal relations while processing input tokens in parallel. While this parallelization makes them computationally efficient it restricts the model from fully exploiting the sequential nature of the input. The representation at a given layer can only access representations from lower layers rather than the higher level representations already available. In this work we propose the Feedback Transformer architecture that exposes all previous representations to all future representations meaning the lowest representation of the current timestep is formed from the highest-level abstract representation of the past. We demonstrate on a variety of benchmarks in language modeling machine translation and reinforcement learning that the increased representation capacity can create small shallow models with much stronger performance than comparable Transformers.
