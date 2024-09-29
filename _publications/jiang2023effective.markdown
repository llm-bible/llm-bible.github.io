---
layout: publication
title: Busefficient And Effective Vision45;language Pre45;training With Bottom45;up Patch Summarization
authors: Jiang Chaoya, Xu Haiyang, Ye Wei, Ye Qinghao, Li Chenliang, Yan Ming, Bi Bin, Zhang Shikun, Huang Fei, Huang Songfang
conference: "Arxiv"
year: 2023
bibkey: jiang2023effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.08504"}
tags: ['Applications', 'Efficiency And Optimization', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Vision Transformer (ViT) based Vision45;Language Pre45;training (VLP) models have demonstrated impressive performance in various tasks. However the lengthy visual token sequences fed into ViT can lead to training inefficiency and ineffectiveness. Existing efforts address the challenge by either bottom45;level patch extraction in the ViT backbone or top45;level patch abstraction outside not balancing training efficiency and effectiveness well. Inspired by text summarization in natural language processing we propose a Bottom45;Up Patch Summarization approach named BUS coordinating bottom45;level extraction and top45;level abstraction to learn a concise summary of lengthy visual token sequences efficiently. Specifically We incorporate a Text45;Semantics45;Aware Patch Selector (TSPS) into the ViT backbone to perform a coarse45;grained visual token extraction and then attach a flexible Transformer45;based Patch Abstraction Decoder (PAD) upon the backbone for top45;level visual abstraction. This bottom45;up collaboration enables our BUS to yield high training efficiency while maintaining or even improving effectiveness. We evaluate our approach on various visual45;language understanding and generation tasks and show competitive downstream task performance while boosting the training efficiency by 5037;. Additionally our model achieves state45;of45;the45;art performance on many downstream tasks by increasing input image resolution without increasing computational costs over baselines.
