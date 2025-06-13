---
layout: publication
title: 'Efficient Length-generalizable Attention Via Causal Retrieval For Long-context Language Modeling'
authors: Xiang Hu, Zhihao Teng, Jun Zhao, Wei Wu, Kewei Tu
conference: "Arxiv"
year: 2024
bibkey: hu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01651"}
tags: ['Transformer', 'Pre-Training', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Despite the success of Transformers, handling long contexts remains challenging due to the limited length generalization and quadratic complexity of self-attention. Thus Transformers often require post-training with a larger attention window, significantly increasing computational and memory costs. In this paper, we propose a novel attention mechanism based on dynamic context, Grouped Cross Attention (GCA), which can generalize to 1000 times the pre-training context length while maintaining the ability to access distant information with a constant attention window size. For a given input sequence, we split it into chunks and use each chunk to retrieve top-k relevant past chunks for subsequent text generation. Specifically, unlike most previous works that use an off-the-shelf retriever, our key innovation allows the retriever to learn how to retrieve past chunks that better minimize the auto-regressive loss of subsequent tokens in an end-to-end manner. Such a mechanism accommodates retrieved chunks with a fixed-size attention window to achieve long-range information access, significantly reducing computational and memory costs during training and inference. Experiments show that GCA-based models achieve near-perfect accuracy in passkey retrieval for 16M context lengths, which is 1000 times the training length.
