---
layout: publication
title: 'Convformer: Revisiting Transformer For Sequential User Modeling'
authors: Hao Wang, Jianxun Lian, Mingqi Wu, Haoxuan Li, Jiajun Fan, Wanyue Xu, Chaozhuo Li, Xing Xie
conference: "Arxiv"
year: 2023
bibkey: wang2023revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.02925"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer']
---
Sequential user modeling, a critical task in personalized recommender
systems, focuses on predicting the next item a user would prefer, requiring a
deep understanding of user behavior sequences. Despite the remarkable success
of Transformer-based models across various domains, their full potential in
comprehending user behavior remains untapped. In this paper, we re-examine
Transformer-like architectures aiming to advance state-of-the-art performance.
We start by revisiting the core building blocks of Transformer-based methods,
analyzing the effectiveness of the item-to-item mechanism within the context of
sequential user modeling. After conducting a thorough experimental analysis, we
identify three essential criteria for devising efficient sequential user
models, which we hope will serve as practical guidelines to inspire and shape
future designs. Following this, we introduce ConvFormer, a simple but powerful
modification to the Transformer architecture that meets these criteria,
yielding state-of-the-art results. Additionally, we present an acceleration
technique to minimize the complexity associated with processing extremely long
sequences. Experiments on four public datasets showcase ConvFormer's
superiority and confirm the validity of our proposed criteria.
