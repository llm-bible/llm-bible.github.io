---
layout: publication
title: Probabilistically Masked Language Model Capable Of Autoregressive Generation In Arbitrary Word Order
authors: Liao Yi, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2020
bibkey: liao2020probabilistically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.11579"}
tags: ['Applications', 'BERT', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Masked language model and autoregressive language model are two types of language models. While pretrained masked language models such as BERT overwhelm the line of natural language understanding (NLU) tasks autoregressive language models such as GPT are especially capable in natural language generation (NLG). In this paper we propose a probabilistic masking scheme for the masked language model which we call probabilistically masked language model (PMLM). We implement a specific PMLM with a uniform prior distribution on the masking ratio named u-PMLM. We prove that u-PMLM is equivalent to an autoregressive permutated language model. One main advantage of the model is that it supports text generation in arbitrary order with surprisingly good quality which could potentially enable new applications over traditional unidirectional generation. Besides the pretrained u-PMLM also outperforms BERT on a set of downstream NLU tasks.
