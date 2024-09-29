---
layout: publication
title: Insertion45;based Decoding With Automatically Inferred Generation Order
authors: Gu Jiatao, Liu Qi, Cho Kyunghyun
conference: "Arxiv"
year: 2019
bibkey: gu2019insertion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1902.01370"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Conventional neural autoregressive decoding commonly assumes a fixed left45;to45;right generation order which may be sub45;optimal. In this work we propose a novel decoding algorithm 45;45; InDIGO 45;45; which supports flexible sequence generation in arbitrary orders through insertion operations. We extend Transformer a state45;of45;the45;art sequence generation model to efficiently implement the proposed approach enabling it to be trained with either a pre45;defined generation order or adaptive orders obtained from beam45;search. Experiments on four real45;world tasks including word order recovery machine translation image caption and code generation demonstrate that our algorithm can generate sequences following arbitrary orders while achieving competitive or even better performance compared to the conventional left45;to45;right generation. The generated sequences show that InDIGO adopts adaptive generation orders based on input information.
