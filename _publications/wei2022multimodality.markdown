---
layout: publication
title: 'MVP: Multimodality-guided Visual Pre-training'
authors: Longhui Wei, Lingxi Xie, Wengang Zhou, Houqiang Li, Qi Tian
conference: "Arxiv"
year: 2022
bibkey: wei2022multimodality
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2203.05175'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
Recently, masked image modeling (MIM) has become a promising direction for
visual pre-training. In the context of vision transformers, MIM learns
effective visual representation by aligning the token-level features with a
pre-defined space (e.g., BEIT used a d-VAE trained on a large image corpus as
the tokenizer). In this paper, we go one step further by introducing guidance
from other modalities and validating that such additional knowledge leads to
impressive gains for visual pre-training. The proposed approach is named
Multimodality-guided Visual Pre-training (MVP), in which we replace the
tokenizer with the vision branch of CLIP, a vision-language model pre-trained
on 400 million image-text pairs. We demonstrate the effectiveness of MVP by
performing standard experiments, i.e., pre-training the ViT models on ImageNet
and fine-tuning them on a series of downstream visual recognition tasks. In
particular, pre-training ViT-Base/16 for 300 epochs, MVP reports a 52.4% mIoU
on ADE20K, surpassing BEIT (the baseline and previous state-of-the-art) with an
impressive margin of 6.8%.
