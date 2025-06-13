---
layout: publication
title: 'Llava-slt: Visual Language Tuning For Sign Language Translation'
authors: Han Liang, Chengyu Huang, Yuecheng Xu, Cheng Tang, Weicai Ye, Juze Zhang, Xin Chen, Jingyi Yu, Lan Xu
conference: "Arxiv"
year: 2024
bibkey: liang2024llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16524"}
tags: ['Tools', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'SLT']
---
In the realm of Sign Language Translation (SLT), reliance on costly
gloss-annotated datasets has posed a significant barrier. Recent advancements
in gloss-free SLT methods have shown promise, yet they often largely lag behind
gloss-based approaches in terms of translation accuracy. To narrow this
performance gap, we introduce LLaVA-SLT, a pioneering Large Multimodal Model
(LMM) framework designed to leverage the power of Large Language Models (LLMs)
through effectively learned visual language embeddings. Our model is trained
through a trilogy. First, we propose linguistic continued pretraining. We scale
up the LLM and adapt it to the sign language domain using an extensive corpus
dataset, effectively enhancing its textual linguistic knowledge about sign
language. Then, we adopt visual contrastive pretraining to align the visual
encoder with a large-scale pretrained text encoder. We propose hierarchical
visual encoder that learns a robust word-level intermediate representation that
is compatible with LLM token embeddings. Finally, we propose visual language
tuning. We freeze pretrained models and employ a lightweight trainable MLP
connector. It efficiently maps the pretrained visual language embeddings into
the LLM token embedding space, enabling downstream SLT task. Our comprehensive
experiments demonstrate that LLaVA-SLT outperforms the state-of-the-art
methods. By using extra annotation-free data, it even closes to the gloss-based
accuracy.
