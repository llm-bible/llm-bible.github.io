---
layout: publication
title: Enhancing Transformers Without Self-supervised Learning: A Loss Landscape Perspective In Sequential Recommendation
authors: Lai Vivian, Chen Huiyuan, Yeh Chin-chia Michael, Xu Minghua, Cai Yiwei, Yang Hao
conference: "Arxiv"
year: 2023
bibkey: lai2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10347"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
Transformer and its variants are a powerful class of architectures for sequential recommendation owing to their ability of capturing a users dynamic interests from their past interactions. Despite their success Transformer-based models often require the optimization of a large number of parameters making them difficult to train from sparse data in sequential recommendation. To address the problem of data sparsity previous studies have utilized self-supervised learning to enhance Transformers such as pre-training embeddings from item attributes or contrastive data augmentations. However these approaches encounter several training issues including initialization sensitivity manual data augmentations and large batch-size memory bottlenecks. In this work we investigate Transformers from the perspective of loss geometry aiming to enhance the models data efficiency and generalization in sequential recommendation. We observe that Transformers (e.g. SASRec) can converge to extremely sharp local minima if not adequately regularized. Inspired by the recent Sharpness-Aware Minimization (SAM) we propose SAMRec which significantly improves the accuracy and robustness of sequential recommendation. SAMRec performs comparably to state-of-the-art self-supervised Transformers such as S^3Rec and CL4SRec without the need for pre-training or strong data augmentations.
