---
layout: publication
title: 'Adapterbias: Parameter-efficient Token-dependent Representation Shift For Adapters In NLP Tasks'
authors: Chin-lun Fu, Zih-ching Chen, Yun-ru Lee, Hung-yi Lee
conference: "Arxiv"
year: 2022
bibkey: fu2022parameter
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.00305'}
tags: ['Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Ethics and Bias', 'Pretraining Methods']
---
Transformer-based pre-trained models with millions of parameters require
large storage. Recent approaches tackle this shortcoming by training adapters,
but these approaches still require a relatively large number of parameters. In
this study, AdapterBias, a surprisingly simple yet effective adapter
architecture, is proposed. AdapterBias adds a token-dependent shift to the
hidden output of transformer layers to adapt to downstream tasks with only a
vector and a linear layer. Extensive experiments are conducted to demonstrate
the effectiveness of AdapterBias. The experiments show that our proposed method
can dramatically reduce the trainable parameters compared to the previous works
with a minimal decrease in task performances compared with fine-tuned
pre-trained models. We further find that AdapterBias automatically learns to
assign more significant representation shifts to the tokens related to the task
in consideration.
