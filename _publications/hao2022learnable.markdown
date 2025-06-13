---
layout: publication
title: 'Learnable Model Augmentation Self-supervised Learning For Sequential Recommendation'
authors: Yongjing Hao, Pengpeng Zhao, Xuefeng Xian, Guanfeng Liu, Deqing Wang, Lei Zhao, Yanchi Liu, Victor S. Sheng
conference: "Arxiv"
year: 2022
bibkey: hao2022learnable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2204.10128'}
tags: ['Training Techniques', 'Pretraining Methods']
---
Sequential Recommendation aims to predict the next item based on user
behaviour. Recently, Self-Supervised Learning (SSL) has been proposed to
improve recommendation performance. However, most of existing SSL methods use a
uniform data augmentation scheme, which loses the sequence correlation of an
original sequence. To this end, in this paper, we propose a Learnable Model
Augmentation self-supervised learning for sequential Recommendation (LMA4Rec).
Specifically, LMA4Rec first takes model augmentation as a supplementary method
for data augmentation to generate views. Then, LMA4Rec uses learnable Bernoulli
dropout to implement model augmentation learnable operations. Next,
self-supervised learning is used between the contrastive views to extract
self-supervised signals from an original sequence. Finally, experiments on
three public datasets show that the LMA4Rec method effectively improves
sequential recommendation performance compared with baseline methods.
