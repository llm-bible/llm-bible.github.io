---
layout: publication
title: Efficient Vision45;and45;language Pre45;training With Text45;relevant Image Patch Selection
authors: Ye Wei, Jiang Chaoya, Xu Haiyang, Ye Chenhao, Li Chenliang, Yan Ming, Zhang Shikun, Huang Songhang, Huang Fei
conference: "Arxiv"
year: 2024
bibkey: ye2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07883"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Vision Transformers (ViTs) have become increasingly popular in large45;scale Vision and Language Pre45;training (VLP) models. Although previous VLP research has demonstrated the efficacy of ViTs these efforts still struggle with computational inefficiencies caused by lengthy visual sequences. To address this challenge we introduce an efficient VLP approach called TRIPS which stands for Text45;Relevant Image Patch Selection. TRIPS progressively reduces the visual sequence using a text45;guided patch45;selection layer in the visual backbone thereby accelerating both training and inference processes. This patch45;selection layer dynamically computes text45;dependent visual attention enabling it to identify attentive image tokens with text guidance and fuse inattentive ones in an end45;to45;end fashion. Importantly TRIPS does not add any extra parameters and generalizes to most ViT45;based VLP models. We incorporate TRIPS into three representative VLP models covering single45;stream dual45;stream and generative paradigms and conduct extensive experiments on five widely45;used multi45;modal benchmark datasets. Our experimental results reveal that TRIPS delivers a 4037; speedup while maintaining competitive or superior performance on downstream tasks.
