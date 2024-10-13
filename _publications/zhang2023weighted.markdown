---
layout: publication
title: 'Weighted Sampling For Masked Language Modeling'
authors: Zhang Linhan, Chen Qian, Wang Wen, Deng Chong, Cao Xin, Hao Kongzhang, Jiang Yuxin, Wang Wei
conference: ""
year: 2023
bibkey: zhang2023weighted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.14225"}
tags: ['BERT', 'Ethics And Bias', 'Fine Tuning', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Masked Language Modeling (MLM) is widely used to pretrain language models.
The standard random masking strategy in MLM causes the pre-trained language
models (PLMs) to be biased toward high-frequency tokens. Representation
learning of rare tokens is poor and PLMs have limited performance on downstream
tasks. To alleviate this frequency bias issue, we propose two simple and
effective Weighted Sampling strategies for masking tokens based on the token
frequency and training loss. We apply these two strategies to BERT and obtain
Weighted-Sampled BERT (WSBERT). Experiments on the Semantic Textual Similarity
benchmark (STS) show that WSBERT significantly improves sentence embeddings
over BERT. Combining WSBERT with calibration methods and prompt learning
further improves sentence embeddings. We also investigate fine-tuning WSBERT on
the GLUE benchmark and show that Weighted Sampling also improves the transfer
learning capability of the backbone PLM. We further analyze and provide
insights into how WSBERT improves token embeddings.
