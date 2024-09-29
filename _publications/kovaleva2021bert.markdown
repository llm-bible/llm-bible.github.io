---
layout: publication
title: BERT Busters Outlier Dimensions That Disrupt Transformers
authors: Kovaleva Olga, Kulshreshtha Saurabh, Rogers Anna, Rumshisky Anna
conference: "Arxiv"
year: 2021
bibkey: kovaleva2021bert
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.06990"}
tags: ['BERT', 'Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Multiple studies have shown that Transformers are remarkably robust to pruning. Contrary to this received wisdom we demonstrate that pre45;trained Transformer encoders are surprisingly fragile to the removal of a very small number of features in the layer outputs (<0.000137; of model weights). In case of BERT and other pre45;trained encoder Transformers the affected component is the scaling factors and biases in the LayerNorm. The outliers are high45;magnitude normalization parameters that emerge early in pre45;training and show up consistently in the same dimensional position throughout the model. We show that disabling them significantly degrades both the MLM loss and the downstream task performance. This effect is observed across several BERT45;family models and other popular pre45;trained Transformer architectures including BART XLNet and ELECTRA; we also show a similar effect in GPT45;2.
