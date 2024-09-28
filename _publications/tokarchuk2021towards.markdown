---
layout: publication
title: Towards Reinforcement Learning for Pivot-based Neural Machine Translation with Non-autoregressive Transformer
authors: Tokarchuk Evgeniia, Rosendahl Jan, Wang Weiyue, Petrushkov Pavel, Lancewicki Tomer, Khadivi Shahram, Ney Hermann
conference: "Arxiv"
year: 2021
bibkey: tokarchuk2021towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.13097"}
tags: ['ARXIV', 'Pretraining Methods', 'Tools', 'Transformer']
---
Pivot-based neural machine translation (NMT) is commonly used in low-resource setups especially for translation between non-English language pairs. It benefits from using high resource source-pivot and pivot-target language pairs and an individual system is trained for both sub-tasks. However these models have no connection during training and the source-pivot model is not optimized to produce the best translation for the source-target task. In this work we propose to train a pivot-based NMT system with the reinforcement learning (RL) approach which has been investigated for various text generation tasks including machine translation (MT). We utilize a non-autoregressive transformer and present an end-to-end pivot-based integrated model enabling training on source-target data.
