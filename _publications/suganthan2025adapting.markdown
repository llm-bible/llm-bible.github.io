---
layout: publication
title: 'Adapting Decoder-based Language Models For Diverse Encoder Downstream Tasks'
authors: Paul Suganthan, Fedor Moiseev, Le Yan, Junru Wu, Jianmo Ni, Jay Han, Imed Zitouni, Enrique Alfonseca, Xuanhui Wang, Zhe Dong
conference: "Arxiv"
year: 2025
bibkey: suganthan2025adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02656"}
tags: ['Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Decoder-based transformers, while revolutionizing language modeling and
scaling to immense sizes, have not completely overtaken encoder-heavy
architectures in natural language processing. Specifically, encoder-only models
remain dominant in tasks like classification, regression, and ranking. This is
primarily due to the inherent structure of decoder-based models, which limits
their direct applicability to these tasks. In this paper, we introduce Gemma
Encoder, adapting the powerful Gemma decoder model to an encoder architecture,
thereby unlocking its potential for a wider range of non-generative
applications. To optimize the adaptation from decoder to encoder, we
systematically analyze various pooling strategies, attention mechanisms, and
hyperparameters (e.g., dropout rate). Furthermore, we benchmark Gemma Encoder
against established approaches on the GLUE benchmarks, and MS MARCO ranking
benchmark, demonstrating its effectiveness and versatility.
