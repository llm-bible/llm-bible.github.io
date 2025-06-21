---
layout: publication
title: BERT, Mbert, Or Bibert? A Study On Contextualized Embeddings For Neural Machine
  Translation
authors: Haoran Xu, Benjamin Van Durme, Kenton Murray
conference: EMNLP 2021
year: 2021
citations: 28
bibkey: xu2021study
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04588'}]
tags: [Masked Language Model, BERT, Prompting, Model Architecture]
---
The success of bidirectional encoders using masked language models, such as
BERT, on numerous natural language processing tasks has prompted researchers to
attempt to incorporate these pre-trained models into neural machine translation
(NMT) systems. However, proposed methods for incorporating pre-trained models
are non-trivial and mainly focus on BERT, which lacks a comparison of the
impact that other pre-trained models may have on translation performance. In
this paper, we demonstrate that simply using the output (contextualized
embeddings) of a tailored and suitable bilingual pre-trained language model
(dubbed BiBERT) as the input of the NMT encoder achieves state-of-the-art
translation performance. Moreover, we also propose a stochastic layer selection
approach and a concept of dual-directional translation model to ensure the
sufficient utilization of contextualized embeddings. In the case of without
using back translation, our best models achieve BLEU scores of 30.45 for En->De
and 38.61 for De->En on the IWSLT'14 dataset, and 31.26 for En->De and 34.94
for De->En on the WMT'14 dataset, which exceeds all published numbers.