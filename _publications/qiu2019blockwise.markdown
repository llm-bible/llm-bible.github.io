---
layout: publication
title: 'Blockwise Self-attention For Long Document Understanding'
authors: Qiu Jiezhong, Ma Hao, Levy Omer, Yih Scott Wen-tau, Wang Sinong, Tang Jie
conference: "Arxiv"
year: 2019
bibkey: qiu2019blockwise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.02972"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Model Architecture', 'RAG', 'Training Techniques', 'Transformer']
---
We present BlockBERT a lightweight and efficient BERT model for better modeling long-distance dependencies. Our model extends BERT by introducing sparse block structures into the attention matrix to reduce both memory consumption and training/inference time which also enables attention heads to capture either short- or long-range contextual information. We conduct experiments on language model pre-training and several benchmark question answering datasets with various paragraph lengths. BlockBERT uses 18.7-36.137; less memory and 12.0-25.137; less time to learn the model. During testing BlockBERT saves 27.837; inference time while having comparable and sometimes better prediction accuracy compared to an advanced BERT-based model RoBERTa.
