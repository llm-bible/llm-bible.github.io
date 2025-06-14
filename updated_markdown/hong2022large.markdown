---
layout: publication
title: 'Cogvideo: Large-scale Pretraining For Text-to-video Generation Via Transformers'
authors: Wenyi Hong, Ming Ding, Wendi Zheng, Xinghan Liu, Jie Tang
conference: "Arxiv"
year: 2022
citations: 98
bibkey: hong2022large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.15868'}
tags: ['Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods']
---
Large-scale pretrained transformers have created milestones in text (GPT-3)
and text-to-image (DALL-E and CogView) generation. Its application to video
generation is still facing many challenges: The potential huge computation cost
makes the training from scratch unaffordable; The scarcity and weak relevance
of text-video datasets hinder the model understanding complex movement
semantics. In this work, we present 9B-parameter transformer CogVideo, trained
by inheriting a pretrained text-to-image model, CogView2. We also propose
multi-frame-rate hierarchical training strategy to better align text and video
clips. As (probably) the first open-source large-scale pretrained text-to-video
model, CogVideo outperforms all publicly available models at a large margin in
machine and human evaluations.
