---
layout: publication
title: 'Cached Transformers: Improving Transformers With Differentiable Memory Cache'
authors: Zhaoyang Zhang, Wenqi Shao, Yixiao Ge, Xiaogang Wang, Jinwei Gu, Ping Luo
conference: "Arxiv"
year: 2023
bibkey: zhang2023cached
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12742"}
tags: ['Transformer', 'Applications', 'Language Modeling', 'Model Architecture', 'Attention Mechanism', 'Training Techniques', 'Pretraining Methods']
---
This work introduces a new Transformer model called Cached Transformer, which
uses Gated Recurrent Cached (GRC) attention to extend the self-attention
mechanism with a differentiable memory cache of tokens. GRC attention enables
attending to both past and current tokens, increasing the receptive field of
attention and allowing for exploring long-range dependencies. By utilizing a
recurrent gating unit to continuously update the cache, our model achieves
significant advancements in \textbf\{six\} language and vision tasks, including
language modeling, machine translation, ListOPs, image classification, object
detection, and instance segmentation. Furthermore, our approach surpasses
previous memory-based techniques in tasks such as language modeling and
displays the ability to be applied to a broader range of situations.
