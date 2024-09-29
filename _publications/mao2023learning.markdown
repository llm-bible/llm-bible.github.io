---
layout: publication
title: LEALLA&#58; Learning Lightweight Language-agnostic Sentence Embeddings With Knowledge Distillation
authors: Mao Zhuoyuan, Nakagawa Tetsuji
conference: "Arxiv"
year: 2023
bibkey: mao2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.08387"}
tags: ['Distillation', 'Efficiency And Optimization']
---
Large-scale language-agnostic sentence embedding models such as LaBSE (Feng et al. 2022) obtain state-of-the-art performance for parallel sentence alignment. However these large-scale models can suffer from inference speed and computation overhead. This study systematically explores learning language-agnostic sentence embeddings with lightweight models. We demonstrate that a thin-deep encoder can construct robust low-dimensional sentence embeddings for 109 languages. With our proposed distillation methods we achieve further improvements by incorporating knowledge from a teacher model. Empirical results on Tatoeba United Nations and BUCC show the effectiveness of our lightweight models. We release our lightweight language-agnostic sentence embedding models LEALLA on TensorFlow Hub.
