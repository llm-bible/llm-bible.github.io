---
layout: publication
title: 'Semantics-aware Attention Improves Neural Machine Translation'
authors: Aviv Slobodkin, Leshem Choshen, Omri Abend
conference: "Arxiv"
year: 2021
bibkey: slobodkin2021semantics
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2110.06920'}
tags: ['Attention Mechanism', 'Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
The integration of syntactic structures into Transformer machine translation
has shown positive results, but to our knowledge, no work has attempted to do
so with semantic structures. In this work we propose two novel parameter-free
methods for injecting semantic information into Transformers, both rely on
semantics-aware masking of (some of) the attention heads. One such method
operates on the encoder, through a Scene-Aware Self-Attention (SASA) head.
Another on the decoder, through a Scene-Aware Cross-Attention (SACrA) head. We
show a consistent improvement over the vanilla Transformer and syntax-aware
models for four language pairs. We further show an additional gain when using
both semantic and syntactic structures in some language pairs.
