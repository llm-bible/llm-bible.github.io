---
layout: publication
title: 'Renaissance: Investigating The Pretraining Of Vision-language Encoders'
authors: Clayton Fields, Casey Kennington
conference: "Arxiv"
year: 2024
bibkey: fields2024investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.06657'}
  - {name: "Code", url: 'https://github.com/bsu-slim/renaissance'}
tags: ['Has Code', 'Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Multimodal Models', 'Survey Paper', 'Pretraining Methods']
---
In the past several years there has been an explosion of available models for
vision-language tasks. Unfortunately, the literature still leaves open a number
of questions related to best practices in designing and training such models.
In this paper we seek to answer several questions related to the pretraining of
vision-language encoders through meta-analysis. In our first set of
experiments, we show that we can save significant compute at no cost to
downstream performance, by freezing large parts of vision-language models
during pretraining. In our second set of experiments we examine the effect of
basing a VL transformer on a vision model versus a text model. Additionally, we
introduce a VL modeling platform called Renaissance that we use to conduct all
of the experiments. This program offers a great deal of flexibility in
creating, training and evaluating transformer encoders for VL modeling. The
source code for Renaissance can be found at
https://github.com/bsu-slim/renaissance.
