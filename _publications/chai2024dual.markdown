---
layout: publication
title: Dual Modalities Of Text Visual And Textual Generative Pre-training
authors: Chai Yekun, Liu Qingyi, Xiao Jingwu, Wang Shuohuan, Sun Yu, Wu Hua
conference: "Arxiv"
year: 2024
bibkey: chai2024dual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10710"}
tags: ['GPT', 'Language Modeling', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Harnessing visual texts represents a burgeoning frontier in the evolution of language modeling. In this paper we introduce a novel pre-training framework for a suite of pixel-based autoregressive language models pre-training on a corpus of over 400 million documents rendered as RGB images. Our approach is characterized by a dual-modality training regimen engaging both visual data through next patch prediction with a regression head and textual data via next token prediction with a classification head. This study is particularly focused on investigating the synergistic interplay between visual and textual modalities of language. Our comprehensive evaluation across a diverse array of benchmarks reveals that the confluence of visual and textual data substantially augments the efficacy of pixel-based language models. Notably our findings show that a unidirectional pixel-based model devoid of textual data during training can match the performance levels of advanced bidirectional pixel-based models on various language understanding benchmarks. This work highlights the considerable untapped potential of integrating visual and textual information for language modeling purposes. We will release our code data and checkpoints to inspire further research advancement.
