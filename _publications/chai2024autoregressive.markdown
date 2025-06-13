---
layout: publication
title: 'Autoregressive Pre-training On Pixels And Texts'
authors: Yekun Chai, Qingyi Liu, Jingwu Xiao, Shuohuan Wang, Yu Sun, Hua Wu
conference: "Arxiv"
year: 2024
bibkey: chai2024autoregressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10710"}
  - {name: "Code", url: "https://github.com/ernie-research/pixelgpt"}
tags: ['Pre-Training', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
The integration of visual and textual information represents a promising
direction in the advancement of language models. In this paper, we explore the
dual modality of language--both visual and textual--within an autoregressive
framework, pre-trained on both document images and texts. Our method employs a
multimodal training strategy, utilizing visual data through next patch
prediction with a regression head and/or textual data through next token
prediction with a classification head. We focus on understanding the
interaction between these two modalities and their combined impact on model
performance. Our extensive evaluation across a wide range of benchmarks shows
that incorporating both visual and textual data significantly improves the
performance of pixel-based language models. Remarkably, we find that a
unidirectional pixel-based model trained solely on visual data can achieve
comparable results to state-of-the-art bidirectional models on several language
understanding tasks. This work uncovers the untapped potential of integrating
visual and textual modalities for more effective language modeling. We release
our code, data, and model checkpoints at
\url\{https://github.com/ernie-research/pixelgpt\}.
