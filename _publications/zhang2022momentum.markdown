---
layout: publication
title: 'Momentum Calibration For Text Generation'
authors: Xingxing Zhang, Yiran Liu, Xun Wang, Pengcheng He, Yang Yu, Si-qing Chen, Wayne Xiong, Furu Wei
conference: "Arxiv"
year: 2022
bibkey: zhang2022momentum
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.04257'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Applications', 'Ethics and Bias', 'Pretraining Methods']
---
The input and output of most text generation tasks can be transformed to two
sequences of tokens and they can be modeled using sequence-to-sequence learning
modeling tools such as Transformers. These models are usually trained by
maximizing the likelihood the output text sequence and assumes the input
sequence and all gold preceding tokens are given during training, while during
inference the model suffers from the exposure bias problem (i.e., it only has
access to its previously predicted tokens rather gold tokens during beam
search). In this paper, we propose MoCa (\{\bf Mo\}mentum \{\bf Ca\}libration) for
text generation. MoCa is an online method that dynamically generates slowly
evolving (but consistent) samples using a momentum moving average generator
with beam search and MoCa learns to align its model scores of these samples
with their actual qualities. Experiments on four text generation datasets
(i.e., CNN/DailyMail, XSum, SAMSum and Gigaword) show MoCa consistently
improves strong pre-trained transformers using vanilla fine-tuning and we
achieve the state-of-the-art results on CNN/DailyMail and SAMSum datasets.
