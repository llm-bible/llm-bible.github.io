---
layout: publication
title: 'Knowledgeable Salient Span Mask For Enhancing Language Models As Knowledge Base'
authors: Cunxiang Wang, Fuli Luo, Yanyang Li, Runxin Xu, Fei Huang, Yue Zhang
conference: "Arxiv"
year: 2022
bibkey: wang2022knowledgeable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.07994"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Pre-Training', 'Attention Mechanism']
---
Pre-trained language models (PLMs) like BERT have made significant progress
in various downstream NLP tasks. However, by asking models to do cloze-style
tests, recent work finds that PLMs are short in acquiring knowledge from
unstructured text. To understand the internal behaviour of PLMs in retrieving
knowledge, we first define knowledge-baring (K-B) tokens and knowledge-free
(K-F) tokens for unstructured text and ask professional annotators to label
some samples manually. Then, we find that PLMs are more likely to give wrong
predictions on K-B tokens and attend less attention to those tokens inside the
self-attention module. Based on these observations, we develop two solutions to
help the model learn more knowledge from unstructured text in a fully
self-supervised manner. Experiments on knowledge-intensive tasks show the
effectiveness of the proposed methods. To our best knowledge, we are the first
to explore fully self-supervised learning of knowledge in continual
pre-training.
