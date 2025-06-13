---
layout: publication
title: 'Merge Then Realign: Simple And Effective Modality-incremental Continual Learning For Multimodal Llms'
authors: Dingkun Zhang, Shuhan Qi, Xinyu Xiao, Kehai Chen, Xuan Wang
conference: "Arxiv"
year: 2025
bibkey: zhang2025merge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.07663'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Multimodal Models', 'Model Architecture']
---
Recent advances in Multimodal Large Language Models (MLLMs) have enhanced
their versatility as they integrate a growing number of modalities. Considering
the heavy cost of training MLLMs, it is necessary to reuse the existing ones
and further extend them to more modalities through Modality-incremental
Continual Learning (MCL). However, this often comes with a performance
degradation in the previously learned modalities. In this work, we revisit the
MCL and investigate a more severe issue it faces in contrast to traditional
continual learning, that its degradation comes not only from catastrophic
forgetting but also from the misalignment between the modality-agnostic and
modality-specific components. To address this problem, we propose an elegantly
simple MCL paradigm called "MErge then ReAlign" (MERA). Our method avoids
introducing heavy training overhead or modifying the model architecture, hence
is easy to deploy and highly reusable in the MLLM community. Extensive
experiments demonstrate that, despite the simplicity of MERA, it shows
impressive performance, holding up to a 99.84% Backward Relative Gain when
extending to four modalities, achieving a nearly lossless MCL performance.
