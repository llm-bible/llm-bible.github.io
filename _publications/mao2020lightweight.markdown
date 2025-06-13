---
layout: publication
title: 'Ladabert: Lightweight Adaptation Of BERT Through Hybrid Model Compression'
authors: Yihuan Mao, Yujing Wang, Chufan Wu, Chen Zhang, Yang Wang, Yaming Yang, Quanlu Zhang, Yunhai Tong, Jing Bai
conference: "Arxiv"
year: 2020
bibkey: mao2020lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.04124"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Distillation', 'Pruning', 'Quantization', 'BERT']
---
BERT is a cutting-edge language representation model pre-trained by a large
corpus, which achieves superior performances on various natural language
understanding tasks. However, a major blocking issue of applying BERT to online
services is that it is memory-intensive and leads to unsatisfactory latency of
user requests, raising the necessity of model compression. Existing solutions
leverage the knowledge distillation framework to learn a smaller model that
imitates the behaviors of BERT. However, the training procedure of knowledge
distillation is expensive itself as it requires sufficient training data to
imitate the teacher model. In this paper, we address this issue by proposing a
hybrid solution named LadaBERT (Lightweight adaptation of BERT through hybrid
model compression), which combines the advantages of different model
compression methods, including weight pruning, matrix factorization and
knowledge distillation. LadaBERT achieves state-of-the-art accuracy on various
public datasets while the training overheads can be reduced by an order of
magnitude.
