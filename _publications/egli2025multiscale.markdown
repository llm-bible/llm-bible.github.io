---
layout: publication
title: 'Multiscale Byte Language Models -- A Hierarchical Architecture For Causal Million-length Sequence Modeling'
authors: Eric Egli, Matteo Manica, Jannis Born
conference: "Arxiv"
year: 2025
bibkey: egli2025multiscale
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14553"}
  - {name: "Code", url: "https://github.com/ai4sd/multiscale-byte-lm"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Tokenization', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Bytes form the basis of the digital world and thus are a promising building
block for multimodal foundation models. Recently, Byte Language Models (BLMs)
have emerged to overcome tokenization, yet the excessive length of bytestreams
requires new architectural paradigms. Therefore, we present the Multiscale Byte
Language Model (MBLM), a model-agnostic hierarchical decoder stack that allows
training with context windows of \\(5\\)M bytes on single GPU in full model
precision. We thoroughly examine MBLM's performance with Transformer and Mamba
blocks on both unimodal and multimodal tasks. Our experiments demonstrate that
hybrid architectures are efficient in handling extremely long byte sequences
during training while achieving near-linear generational efficiency. To the
best of our knowledge, we present the first evaluation of BLMs on visual Q\&A
tasks and find that, despite serializing images and the absence of an encoder,
a MBLM with pure next token prediction can match custom CNN-LSTM architectures
with designated classification heads. We show that MBLMs exhibit strong
adaptability in integrating diverse data representations, including pixel and
image filestream bytes, underlining their potential toward omnimodal foundation
models. Source code is publicly available at:
https://github.com/ai4sd/multiscale-byte-lm
