---
layout: publication
title: 'Deconvolution-based Global Decoding For Neural Machine Translation'
authors: Junyang Lin, Xu Sun, Xuancheng Ren, Shuming Ma, Jinsong Su, Qi Su
conference: "Arxiv"
year: 2018
bibkey: lin2018deconvolution
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1806.03692"}
tags: ['Applications']
---
A great proportion of sequence-to-sequence (Seq2Seq) models for Neural
Machine Translation (NMT) adopt Recurrent Neural Network (RNN) to generate
translation word by word following a sequential order. As the studies of
linguistics have proved that language is not linear word sequence but sequence
of complex structure, translation at each step should be conditioned on the
whole target-side context. To tackle the problem, we propose a new NMT model
that decodes the sequence with the guidance of its structural prediction of the
context of the target sequence. Our model generates translation based on the
structural prediction of the target-side context so that the translation can be
freed from the bind of sequential order. Experimental results demonstrate that
our model is more competitive compared with the state-of-the-art methods, and
the analysis reflects that our model is also robust to translating sentences of
different lengths and it also reduces repetition with the instruction from the
target-side context for decoding.
