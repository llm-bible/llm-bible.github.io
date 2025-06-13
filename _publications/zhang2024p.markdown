---
layout: publication
title: 'P-mod: Building Mixture-of-depths Mllms Via Progressive Ratio Decay'
authors: Jun Zhang, Desen Meng, Ji Qi, Zhenpeng Huang, Tao Wu, Limin Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024p
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04449"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Despite the remarkable performance of multimodal large language models
(MLLMs) across diverse tasks, the substantial training and inference costs
impede their advancement. The majority of computation stems from the
overwhelming volume of vision tokens processed by the transformer decoder. In
this paper, we propose to build efficient MLLMs by leveraging the
Mixture-of-Depths (MoD) mechanism, where each transformer decoder layer selects
essential vision tokens to process while skipping redundant ones. However,
integrating MoD into MLLMs is non-trivial. To address the challenges of
training and inference stability as well as limited training data, we adapt the
MoD module with two novel designs: tanh-gated weight normalization (TanhNorm)
and symmetric token reweighting (STRing). Moreover, we observe that vision
tokens exhibit higher redundancy in deeper layer and thus design a progressive
ratio decay (PRD) strategy, which gradually reduces the token retention ratio
layer by layer, employing a shifted cosine schedule. This crucial design fully
unleashes the potential of MoD, significantly boosting the efficiency and
performance of our models. To validate the effectiveness of our approach, we
conduct extensive experiments with two baseline models across 14 benchmarks.
Our model, p-MoD, matches or even surpasses the performance of the baseline
models, with only 55.6% TFLOPs and 53.8% KV cache storage during inference, and
77.7% GPU hours during training.
