---
layout: publication
title: 'Utilize Transformers For Translating Wikipedia Category Names'
authors: Hoang-thang Ta, Quoc Thang La
conference: "Arxiv"
year: 2024
bibkey: ta2024utilize
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.06124'}
tags: ['RAG', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
On Wikipedia, articles are categorized to aid readers in navigating content
efficiently. The manual creation of new categories can be laborious and
time-intensive. To tackle this issue, we built language models to translate
Wikipedia categories from English to Vietnamese with a dataset containing
15,000 English-Vietnamese category pairs. Subsequently, small to medium-scale
Transformer pre-trained models with a sequence-to-sequence architecture were
fine-tuned for category translation. The experiments revealed that
OPUS-MT-en-vi surpassed other models, attaining the highest performance with a
BLEU score of 0.73, despite its smaller model storage. We expect our paper to
be an alternative solution for translation tasks with limited computer
resources.
