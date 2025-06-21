---
layout: publication
title: A Tensorized Transformer For Language Modeling
authors: Xindian Ma et al.
conference: Arxiv
year: 2019
citations: 63
bibkey: ma2019tensorized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.09777'}]
tags: [Transformer, Language Modeling]
---
Latest development of neural models has connected the encoder and decoder
through a self-attention mechanism. In particular, Transformer, which is solely
based on self-attention, has led to breakthroughs in Natural Language
Processing (NLP) tasks. However, the multi-head attention mechanism, as a key
component of Transformer, limits the effective deployment of the model to a
resource-limited setting. In this paper, based on the ideas of tensor
decomposition and parameters sharing, we propose a novel self-attention model
(namely Multi-linear attention) with Block-Term Tensor Decomposition (BTD). We
test and verify the proposed attention method on three language modeling tasks
(i.e., PTB, WikiText-103 and One-billion) and a neural machine translation task
(i.e., WMT-2016 English-German). Multi-linear attention can not only largely
compress the model parameters but also obtain performance improvements,
compared with a number of language modeling approaches, such as Transformer,
Transformer-XL, and Transformer with tensor train decomposition.