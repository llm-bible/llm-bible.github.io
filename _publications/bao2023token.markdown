---
layout: publication
title: 'Token-level Fitting Issues Of Seq2seq Models'
authors: Guangsheng Bao, Zhiyang Teng, Yue Zhang
conference: "Arxiv"
year: 2023
bibkey: bao2023token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.04493"}
tags: ['Pretraining Methods', 'Training Techniques', 'Reinforcement Learning']
---
Sequence-to-sequence (seq2seq) models have been widely used for natural
language processing, computer vision, and other deep learning tasks. We find
that seq2seq models trained with early-stopping suffer from issues at the token
level. In particular, while some tokens in the vocabulary demonstrate
overfitting, others underfit when training is stopped. Experiments show that
the phenomena are pervasive in different models, even in fine-tuned large
pretrained-models. We identify three major factors that influence token-level
fitting, which include token frequency, parts-of-speech, and prediction
discrepancy. Further, we find that external factors such as language, model
size, domain, data scale, and pretraining can also influence the fitting of
tokens.
