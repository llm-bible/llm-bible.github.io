---
layout: publication
title: 'Latent Topic Conversational Models'
authors: Tsung-hsien Wen, Minh-thang Luong
conference: "Arxiv"
year: 2018
bibkey: wen2018latent
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1809.07070'}
tags: ['Training Techniques']
---
Latent variable models have been a preferred choice in conversational
modeling compared to sequence-to-sequence (seq2seq) models which tend to
generate generic and repetitive responses. Despite so, training latent variable
models remains to be difficult. In this paper, we propose Latent Topic
Conversational Model (LTCM) which augments seq2seq with a neural latent topic
component to better guide response generation and make training easier. The
neural topic component encodes information from the source sentence to build a
global "topic" distribution over words, which is then consulted by the seq2seq
model at each generation step. We study in details how the latent
representation is learnt in both the vanilla model and LTCM. Our extensive
experiments contribute to better understanding and training of conditional
latent models for languages. Our results show that by sampling from the learnt
latent representations, LTCM can generate diverse and interesting responses. In
a subjective human evaluation, the judges also confirm that LTCM is the overall
preferred option.
