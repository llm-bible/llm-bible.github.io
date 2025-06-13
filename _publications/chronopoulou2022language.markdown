---
layout: publication
title: 'Language-family Adapters For Low-resource Multilingual Neural Machine Translation'
authors: Alexandra Chronopoulou, Dario Stojanovski, Alexander Fraser
conference: "Arxiv"
year: 2022
bibkey: chronopoulou2022language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2209.15236'}
tags: ['RAG', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
Large multilingual models trained with self-supervision achieve
state-of-the-art results in a wide range of natural language processing tasks.
Self-supervised pretrained models are often fine-tuned on parallel data from
one or multiple language pairs for machine translation. Multilingual
fine-tuning improves performance on low-resource languages but requires
modifying the entire model and can be prohibitively expensive. Training a new
adapter on each language pair or training a single adapter on all language
pairs without updating the pretrained model has been proposed as a
parameter-efficient alternative. However, the former does not permit any
sharing between languages, while the latter shares parameters for all languages
and is susceptible to negative interference. In this paper, we propose training
language-family adapters on top of mBART-50 to facilitate cross-lingual
transfer. Our approach outperforms related baselines, yielding higher
translation scores on average when translating from English to 17 different
low-resource languages. We also show that language-family adapters provide an
effective method to translate to languages unseen during pretraining.
