---
layout: publication
title: 'Enhancing CTR Prediction Through Sequential Recommendation Pre-training: Introducing The SRP4CTR Framework'
authors: Ruidong Han, Qianzhong Li, He Jiang, Rui Li, Yurou Zhao, Xiang Li, Wei Lin
conference: "Arxiv"
year: 2024
bibkey: han2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19658"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Understanding user interests is crucial for Click-Through Rate (CTR)
prediction tasks. In sequential recommendation, pre-training from user
historical behaviors through self-supervised learning can better comprehend
user dynamic preferences, presenting the potential for direct integration with
CTR tasks. Previous methods have integrated pre-trained models into downstream
tasks with the sole purpose of extracting semantic information or
well-represented user features, which are then incorporated as new features.
However, these approaches tend to ignore the additional inference costs to the
downstream tasks, and they do not consider how to transfer the effective
information from the pre-trained models for specific estimated items in CTR
prediction. In this paper, we propose a Sequential Recommendation Pre-training
framework for CTR prediction (SRP4CTR) to tackle the above problems. Initially,
we discuss the impact of introducing pre-trained models on inference costs.
Subsequently, we introduced a pre-trained method to encode sequence side
information concurrently.During the fine-tuning process, we incorporate a
cross-attention block to establish a bridge between estimated items and the
pre-trained model at a low cost. Moreover, we develop a querying transformer
technique to facilitate the knowledge transfer from the pre-trained model to
industrial CTR models. Offline and online experiments show that our method
outperforms previous baseline models.
