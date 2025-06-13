---
layout: publication
title: 'Parameter-efficient Tuning With Special Token Adaptation'
authors: Xiaocong Yang, James Y. Huang, Wenxuan Zhou, Muhao Chen
conference: "Arxiv"
year: 2022
bibkey: yang2022parameter
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.04382'}
tags: ['Attention Mechanism', 'Transformer', 'BERT', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Parameter-efficient tuning aims at updating only a small subset of parameters
when adapting a pretrained model to downstream tasks. In this work, we
introduce PASTA, in which we only modify the special token representations
(e.g., [SEP] and [CLS] in BERT) before the self-attention module at each layer
in Transformer-based models. PASTA achieves comparable performance to full
finetuning in natural language understanding tasks including text
classification and NER with up to only 0.029% of total parameters trained. Our
work not only provides a simple yet effective way of parameter-efficient
tuning, which has a wide range of practical applications when deploying
finetuned models for multiple tasks, but also demonstrates the pivotal role of
special tokens in pretrained language models
