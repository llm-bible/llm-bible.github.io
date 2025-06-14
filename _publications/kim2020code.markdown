---
layout: publication
title: 'Code Prediction By Feeding Trees To Transformers'
authors: Seohyun Kim, Jinman Zhao, Yuchi Tian, Satish Chandra
conference: "Arxiv"
year: 2020
citations: 156
bibkey: kim2020code
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2003.13848'}
tags: ['Transformer', 'Model Architecture', 'Pretraining Methods']
---
We advance the state-of-the-art in the accuracy of code prediction (next
token prediction) used in autocomplete systems. First, we report that using the
recently proposed Transformer architecture even out-of-the-box outperforms
previous neural and non-neural systems for code prediction. We then show that
by making the Transformer architecture aware of the syntactic structure of
code, we further increase the margin by which a Transformer-based system
outperforms previous systems. With this, it outperforms the accuracy of an
RNN-based system (similar to Hellendoorn et al. 2018) by 18.3%, the Deep3
system (Raychev et al 2016) by 14.1%, and an adaptation of Code2Seq (Alon et
al., 2018) for code prediction by 14.4%.
  We present in the paper several ways of communicating the code structure to
the Transformer, which is fundamentally built for processing sequence data. We
provide a comprehensive experimental evaluation of our proposal, along with
alternative design choices, on a standard Python dataset, as well as on a
Facebook internal Python corpus. Our code and data preparation pipeline will be
available in open source.
