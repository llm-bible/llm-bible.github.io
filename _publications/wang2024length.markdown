---
layout: publication
title: 'Length Generalization Of Causal Transformers Without Position Encoding'
authors: Jie Wang, Tao Ji, Yuanbin Wu, Hang Yan, Tao Gui, Qi Zhang, Xuanjing Huang, Xiaoling Wang
conference: "Arxiv"
year: 2024
bibkey: wang2024length
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12224"}
tags: ['Fine-Tuning', 'Transformer', 'Model Architecture', 'Language Modeling', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
Generalizing to longer sentences is important for recent Transformer-based
language models. Besides algorithms manipulating explicit position features,
the success of Transformers without position encodings (NoPE) provides a new
way to overcome the challenge. In this paper, we study the length
generalization property of NoPE. We find that although NoPE can extend to
longer sequences than the commonly used explicit position encodings, it still
has a limited context length. We identify a connection between the failure of
NoPE's generalization and the distraction of attention distributions. We
propose a parameter-efficient tuning for searching attention heads' best
temperature hyper-parameters, which substantially expands NoPE's context size.
Experiments on long sequence language modeling, the synthetic passkey retrieval
task and real-world long context tasks show that NoPE can achieve competitive
performances with state-of-the-art length generalization algorithms. The source
code is publicly accessible
