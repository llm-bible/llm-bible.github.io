---
layout: publication
title: 'Videberta: A Powerful Pre-trained Language Model For Vietnamese'
authors: Cong Dao Tran, Nhut Huy Pham, Anh Nguyen, Truong Son Hy, Tu Vu
conference: "Arxiv"
year: 2023
bibkey: tran2023powerful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.10439"}
  - {name: "Code", url: "https://github.com/HySonLab/ViDeBERTa"}
tags: ['Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Has Code', 'Applications']
---
This paper presents ViDeBERTa, a new pre-trained monolingual language model
for Vietnamese, with three versions - ViDeBERTa_xsmall, ViDeBERTa_base, and
ViDeBERTa_large, which are pre-trained on a large-scale corpus of high-quality
and diverse Vietnamese texts using DeBERTa architecture. Although many
successful pre-trained language models based on Transformer have been widely
proposed for the English language, there are still few pre-trained models for
Vietnamese, a low-resource language, that perform good results on downstream
tasks, especially Question answering. We fine-tune and evaluate our model on
three important natural language downstream tasks, Part-of-speech tagging,
Named-entity recognition, and Question answering. The empirical results
demonstrate that ViDeBERTa with far fewer parameters surpasses the previous
state-of-the-art models on multiple Vietnamese-specific natural language
understanding tasks. Notably, ViDeBERTa_base with 86M parameters, which is only
about 23% of PhoBERT_large with 370M parameters, still performs the same or
better results than the previous state-of-the-art model. Our ViDeBERTa models
are available at: https://github.com/HySonLab/ViDeBERTa.
