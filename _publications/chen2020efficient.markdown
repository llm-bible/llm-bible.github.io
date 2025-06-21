---
layout: publication
title: 'Earlybert: Efficient BERT Training Via Early-bird Lottery Tickets'
authors: Xiaohan Chen et al.
conference: Arxiv
year: 2020
citations: 18
bibkey: chen2020efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.00063'}, {name: Code,
    url: 'https://github.com/VITA-Group/EarlyBERT'}]
tags: [Pre-Training, Fine-Tuning, Transformer, BERT, Efficiency and Optimization]
---
Heavily overparameterized language models such as BERT, XLNet and T5 have
achieved impressive success in many NLP tasks. However, their high model
complexity requires enormous computation resources and extremely long training
time for both pre-training and fine-tuning. Many works have studied model
compression on large NLP models, but only focusing on reducing inference time
while still requiring an expensive training process. Other works use extremely
large batch sizes to shorten the pre-training time, at the expense of higher
computational resource demands. In this paper, inspired by the Early-Bird
Lottery Tickets recently studied for computer vision tasks, we propose
EarlyBERT, a general computationally-efficient training algorithm applicable to
both pre-training and fine-tuning of large-scale language models. By slimming
the self-attention and fully-connected sub-layers inside a transformer, we are
the first to identify structured winning tickets in the early stage of BERT
training. We apply those tickets towards efficient BERT training, and conduct
comprehensive pre-training and fine-tuning experiments on GLUE and SQuAD
downstream tasks. Our results show that EarlyBERT achieves comparable
performance to standard BERT, with 35~45% less training time. Code is available
at https://github.com/VITA-Group/EarlyBERT.