---
layout: publication
title: BERT Busters Outlier Dimensions that Disrupt Transformers
authors: Kovaleva Olga, Kulshreshtha Saurabh, Rogers Anna, Rumshisky Anna
conference: "Arxiv"
year: 2021
bibkey: kovaleva2021bert
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.06990"}
tags: ['ARXIV', 'BERT', 'GPT', 'Model Architecture', 'PRE Training', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Multiple studies have shown that Transformers are remarkably robust to pruning. Contrary to this received wisdom we demonstrate that pre-trained Transformer encoders are surprisingly fragile to the removal of a very small number of features in the layer outputs (<0.0001 of model weights). In case of BERT and other pre-trained encoder Transformers the affected component is the scaling factors and biases in the LayerNorm. The outliers are high-magnitude normalization parameters that emerge early in pre-training and show up consistently in the same dimensional position throughout the model. We show that disabling them significantly degrades both the MLM loss and the downstream task performance. This effect is observed across several BERT-family models and other popular pre-trained Transformer architectures including BART XLNet and ELECTRA; we also show a similar effect in GPT-2.
