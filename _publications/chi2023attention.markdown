---
layout: publication
title: Attention Alignment and Flexible Positional Embeddings Improve Transformer Length Extrapolation
authors: Chi Ta-chung, Fan Ting-han, Rudnicky Alexander I.
conference: "Arxiv"
year: 2023
bibkey: chi2023attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00684"}
tags: ['ARXIV', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'Transformer']
---
An ideal length-extrapolatable Transformer language model can handle sequences longer than the training length without any fine-tuning. Such long-context utilization capability relies heavily on a flexible positional embedding design. Upon investigating the flexibility of existing large pre-trained Transformer language models we find that the T5 family deserves a closer look as its positional embeddings capture rich and flexible attention patterns. However T5 suffers from the dispersed attention issue the longer the input sequence the flatter the attention distribution. To alleviate the issue we propose two attention alignment strategies via temperature scaling. Our findings show improvement on the long-context utilization capability of T5 on language modeling retrieval multi-document question answering and code completion tasks without any fine-tuning. This suggests that a flexible positional embedding design and attention alignment can go a long way toward Transformer length extrapolation.
