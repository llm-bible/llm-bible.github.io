---
layout: publication
title: 'Imputing Out-of-vocabulary Embeddings With LOVE Makes Language Models Robust With Little Cost'
authors: Lihu Chen, Gaël Varoquaux, Fabian M. Suchanek
conference: "Arxiv"
year: 2022
bibkey: chen2022imputing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2203.07860'}
tags: ['Security', 'Model Architecture', 'BERT', 'Tools', 'Pretraining Methods']
---
State-of-the-art NLP systems represent inputs with word embeddings, but these
are brittle when faced with Out-of-Vocabulary (OOV) words. To address this
issue, we follow the principle of mimick-like models to generate vectors for
unseen words, by learning the behavior of pre-trained embeddings using only the
surface form of words. We present a simple contrastive learning framework,
LOVE, which extends the word representation of an existing pre-trained language
model (such as BERT), and makes it robust to OOV with few additional
parameters. Extensive evaluations demonstrate that our lightweight model
achieves similar or even better performances than prior competitors, both on
original datasets and on corrupted variants. Moreover, it can be used in a
plug-and-play fashion with FastText and BERT, where it significantly improves
their robustness.
