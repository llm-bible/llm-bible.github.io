---
layout: publication
title: 'Scaling Language-free Visual Representation Learning'
authors: David Fan, Shengbang Tong, Jiachen Zhu, Koustuv Sinha, Zhuang Liu, Xinlei Chen, Michael Rabbat, Nicolas Ballas, Yann Lecun, Amir Bar, Saining Xie
conference: "Arxiv"
year: 2025
bibkey: fan2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.01017"}
tags: ['Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'TACL', 'RAG', 'Pretraining Methods', 'ACL', 'Applications']
---
Visual Self-Supervised Learning (SSL) currently underperforms Contrastive
Language-Image Pretraining (CLIP) in multimodal settings such as Visual
Question Answering (VQA). This multimodal gap is often attributed to the
semantics introduced by language supervision, even though visual SSL and CLIP
models are often trained on different data. In this work, we ask the question:
"Do visual self-supervised approaches lag behind CLIP due to the lack of
language supervision, or differences in the training data?" We study this
question by training both visual SSL and CLIP models on the same MetaCLIP data,
and leveraging VQA as a diverse testbed for vision encoders. In this controlled
setup, visual SSL models scale better than CLIP models in terms of data and
model capacity, and visual SSL performance does not saturate even after scaling
up to 7B parameters. Consequently, we observe visual SSL methods achieve
CLIP-level performance on a wide range of VQA and classic vision benchmarks.
These findings demonstrate that pure visual SSL can match language-supervised
visual pretraining at scale, opening new opportunities for vision-centric
representation learning.
