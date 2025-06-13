---
layout: publication
title: 'Decoder-only Streaming Transformer For Simultaneous Translation'
authors: Shoutao Guo, Shaolei Zhang, Yang Feng
conference: "Arxiv"
year: 2024
bibkey: guo2024decoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03878"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Simultaneous Machine Translation (SiMT) generates translation while reading
source tokens, essentially producing the target prefix based on the source
prefix. To achieve good performance, it leverages the relationship between
source and target prefixes to exact a policy to guide the generation of
translations. Although existing SiMT methods primarily focus on the
Encoder-Decoder architecture, we explore the potential of Decoder-only
architecture, owing to its superior performance in various tasks and its
inherent compatibility with SiMT. However, directly applying the Decoder-only
architecture to SiMT poses challenges in terms of training and inference. To
alleviate the above problems, we propose the first Decoder-only SiMT model,
named Decoder-only Streaming Transformer (DST). Specifically, DST separately
encodes the positions of the source and target prefixes, ensuring that the
position of the target prefix remains unaffected by the expansion of the source
prefix. Furthermore, we propose a Streaming Self-Attention (SSA) mechanism
tailored for the Decoder-only architecture. It is capable of obtaining
translation policy by assessing the sufficiency of input source information and
integrating with the soft-attention mechanism to generate translations.
Experiments demonstrate that our approach achieves state-of-the-art performance
on three translation tasks.
