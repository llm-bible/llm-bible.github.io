---
layout: publication
title: 'Efficient Vision-and-language Pre-training With Text-relevant Image Patch Selection'
authors: Wei Ye, Chaoya Jiang, Haiyang Xu, Chenhao Ye, Chenliang Li, Ming Yan, Shikun Zhang, Songhang Huang, Fei Huang
conference: "Arxiv"
year: 2024
bibkey: ye2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.07883'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
Vision Transformers (ViTs) have become increasingly popular in large-scale
Vision and Language Pre-training (VLP) models. Although previous VLP research
has demonstrated the efficacy of ViTs, these efforts still struggle with
computational inefficiencies caused by lengthy visual sequences. To address
this challenge, we introduce an efficient VLP approach called TRIPS, which
stands for Text-Relevant Image Patch Selection. TRIPS progressively reduces the
visual sequence using a text-guided patch-selection layer in the visual
backbone, thereby accelerating both training and inference processes. This
patch-selection layer dynamically computes text-dependent visual attention,
enabling it to identify attentive image tokens with text guidance and fuse
inattentive ones in an end-to-end fashion. Importantly, TRIPS does not add any
extra parameters and generalizes to most ViT-based VLP models. We incorporate
TRIPS into three representative VLP models covering single-stream, dual-stream,
and generative paradigms, and conduct extensive experiments on five widely-used
multi-modal benchmark datasets. Our experimental results reveal that TRIPS
delivers a 40% speedup, while maintaining competitive or superior performance
on downstream tasks.
