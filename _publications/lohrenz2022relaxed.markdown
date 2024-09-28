---
layout: publication
title: Relaxed Attention for Transformer Models
authors: Lohrenz Timo, Möller Björn, Li Zhengyang, Fingscheidt Tim
conference: "Arxiv"
year: 2022
bibkey: lohrenz2022relaxed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.09735"}
tags: ['ARXIV', 'Pretraining Methods', 'Transformer']
---
The powerful modeling capabilities of all-attention-based transformer architectures often cause overfitting and - for natural language processing tasks - lead to an implicitly learned internal language model in the autoregressive transformer decoder complicating the integration of external language models. In this paper we explore relaxed attention a simple and easy-to-implement smoothing of the attention weights yielding a two-fold improvement to the general transformer architecture First relaxed attention provides regularization when applied to the self-attention layers in the encoder. Second we show that it naturally supports the integration of an external language model as it suppresses the implicitly learned internal language model by relaxing the cross attention in the decoder. We demonstrate the benefit of relaxed attention across several tasks with clear improvement in combination with recent benchmark approaches. Specifically we exceed the former state-of-the-art performance of 26.90 word error rate on the largest public lip-reading LRS3 benchmark with a word error rate of 26.31 as well as we achieve a top-performing BLEU score of 37.67 on the IWSLT14 (DErightarrowEN) machine translation task without external language models and virtually no additional model parameters. Code and models will be made publicly available.
