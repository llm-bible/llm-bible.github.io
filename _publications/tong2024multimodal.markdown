---
layout: publication
title: 'Metamorph: Multimodal Understanding And Generation Via Instruction Tuning'
authors: Shengbang Tong, David Fan, Jiachen Zhu, Yunyang Xiong, Xinlei Chen, Koustuv Sinha, Michael Rabbat, Yann Lecun, Saining Xie, Zhuang Liu
conference: "Arxiv"
year: 2024
bibkey: tong2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14164"}
tags: ['Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods']
---
In this work, we propose Visual-Predictive Instruction Tuning (VPiT) - a
simple and effective extension to visual instruction tuning that enables a
pretrained LLM to quickly morph into an unified autoregressive model capable of
generating both text and visual tokens. VPiT teaches an LLM to predict discrete
text tokens and continuous visual tokens from any input sequence of image and
text data curated in an instruction-following format. Our empirical
investigation reveals several intriguing properties of VPiT: (1) visual
generation ability emerges as a natural byproduct of improved visual
understanding, and can be unlocked efficiently with a small amount of
generation data; (2) while we find understanding and generation to be mutually
beneficial, understanding data contributes to both capabilities more
effectively than generation data. Building upon these findings, we train our
MetaMorph model and achieve competitive performance on both visual
understanding and generation. In visual generation, MetaMorph can leverage the
world knowledge and reasoning abilities gained from LLM pretraining, and
overcome common failure modes exhibited by other generation models. Our results
suggest that LLMs may have strong "prior" vision capabilities that can be
efficiently adapted to both visual understanding and generation with a
relatively simple instruction tuning process.
