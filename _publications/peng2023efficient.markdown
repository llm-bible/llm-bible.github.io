---
layout: publication
title: Efficient End-to-End Video Question Answering with Pyramidal Multimodal Transformer
authors: Peng Min, Wang Chongyang, Shi Yu, Zhou Xiang-dong
conference: "Arxiv"
year: 2023
bibkey: peng2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.02136"}
tags: ['ARXIV', 'Model Architecture', 'Transformer']
---
This paper presents a new method for end-to-end Video Question Answering (VideoQA) aside from the current popularity of using large-scale pre-training with huge feature extractors. We achieve this with a pyramidal multimodal transformer (PMT) model which simply incorporates a learnable word embedding layer a few convolutional and transformer layers. We use the anisotropic pyramid to fulfill video-language interactions across different spatio-temporal scales. In addition to the canonical pyramid which includes both bottom-up and top-down pathways with lateral connections novel strategies are proposed to decompose the visual feature stream into spatial and temporal sub-streams at different scales and implement their interactions with the linguistic semantics while preserving the integrity of local and global semantics. We demonstrate better or on-par performances with high computational efficiency against state-of-the-art methods on five VideoQA benchmarks. Our ablation study shows the scalability of our model that achieves competitive results for text-to-video retrieval by leveraging feature extractors with reusable pre-trained weights and also the effectiveness of the pyramid.
