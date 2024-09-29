---
layout: publication
title: Token45;level Adaptive Training For Neural Machine Translation
authors: Gu Shuhao, Zhang Jinchao, Meng Fandong, Feng Yang, Xie Wanying, Zhou Jie, Yu Dong
conference: "Arxiv"
year: 2020
bibkey: gu2020token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.04380"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Training Techniques']
---
There exists a token imbalance phenomenon in natural language as different tokens appear with different frequencies which leads to different learning difficulties for tokens in Neural Machine Translation (NMT). The vanilla NMT model usually adopts trivial equal45;weighted objectives for target tokens with different frequencies and tends to generate more high45;frequency tokens and less low45;frequency tokens compared with the golden token distribution. However low45;frequency tokens may carry critical semantic information that will affect the translation quality once they are neglected. In this paper we explored target token45;level adaptive objectives based on token frequencies to assign appropriate weights for each target token during training. We aimed that those meaningful but relatively low45;frequency words could be assigned with larger weights in objectives to encourage the model to pay more attention to these tokens. Our method yields consistent improvements in translation quality on ZH45;EN EN45;RO and EN45;DE translation tasks especially on sentences that contain more low45;frequency tokens where we can get 1.68 1.02 and 0.52 BLEU increases compared with baseline respectively. Further analyses show that our method can also improve the lexical diversity of translation.
