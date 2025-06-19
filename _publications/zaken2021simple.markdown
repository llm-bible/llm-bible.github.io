---
layout: publication
title: 'Bitfit: Simple Parameter-efficient Fine-tuning For Transformer-based Masked
  Language-models'
authors: Elad Ben Zaken, Shauli Ravfogel, Yoav Goldberg
conference: Arxiv
year: 2021
citations: 182
bibkey: zaken2021simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.10199'}]
tags: [Fine-Tuning, Transformer, BERT]
---
We introduce BitFit, a sparse-finetuning method where only the bias-terms of
the model (or a subset of them) are being modified. We show that with
small-to-medium training data, applying BitFit on pre-trained BERT models is
competitive with (and sometimes better than) fine-tuning the entire model. For
larger data, the method is competitive with other sparse fine-tuning methods.
Besides their practical utility, these findings are relevant for the question
of understanding the commonly-used process of finetuning: they support the
hypothesis that finetuning is mainly about exposing knowledge induced by
language-modeling training, rather than learning new task-specific linguistic
knowledge.