---
layout: publication
title: 'Modular Transformers: Compressing Transformers Into Modularized Layers For Flexible Efficient Inference'
authors: Wangchunshu Zhou, Ronan Le Bras, Yejin Choi
conference: "Arxiv"
year: 2023
bibkey: zhou2023modular
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.02379'}
tags: ['Language Modeling', 'Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Tools', 'Quantization', 'Applications', 'Pretraining Methods']
---
Pre-trained Transformer models like T5 and BART have advanced the state of
the art on a wide range of text generation tasks. Compressing these models into
smaller ones has become critically important for practical use. Common neural
network compression techniques such as knowledge distillation or quantization
are limited to static compression where the compression ratio is fixed. In this
paper, we introduce Modular Transformers, a modularized encoder-decoder
framework for flexible sequence-to-sequence model compression. Modular
Transformers train modularized layers that have the same function of two or
more consecutive layers in the original model via module replacing and
knowledge distillation. After training, the modularized layers can be flexibly
assembled into sequence-to-sequence models that meet different
performance-efficiency trade-offs. Experimental results show that after a
single training phase, by simply varying the assembling strategy, Modular
Transformers can achieve flexible compression ratios from 1.1x to 6x with
little to moderate relative performance drop.
