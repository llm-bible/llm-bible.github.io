---
layout: publication
title: 'ICPC: Instance-conditioned Prompting With Contrastive Learning For Semantic Segmentation'
authors: Chaohui Yu, Qiang Zhou, Zhibin Wang, Fan Wang
conference: "Arxiv"
year: 2023
bibkey: yu2023instance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07078"}
tags: ['Tools', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Modern supervised semantic segmentation methods are usually finetuned based
on the supervised or self-supervised models pre-trained on ImageNet. Recent
work shows that transferring the knowledge from CLIP to semantic segmentation
via prompt learning can achieve promising performance. The performance boost
comes from the feature enhancement with multimodal alignment, i.e., the dot
product between vision and text embeddings. However, how to improve the
multimodal alignment for better transfer performance in dense tasks remains
underexplored. In this work, we focus on improving the quality of vision-text
alignment from two aspects of prompting design and loss function, and present
an instance-conditioned prompting with contrastive learning (ICPC) framework.
First, compared with the static prompt designs, we reveal that dynamic
prompting conditioned on image content can more efficiently utilize the text
encoder for complex dense tasks. Second, we propose an align-guided contrastive
loss to refine the alignment of vision and text embeddings. We further propose
lightweight multi-scale alignment for better performance. Extensive experiments
on three large-scale datasets (ADE20K, COCO-Stuff10k, and ADE20K-Full)
demonstrate that ICPC brings consistent improvements across diverse backbones.
Taking ResNet-50 as an example, ICPC outperforms the state-of-the-art
counterpart by 1.71%, 1.05%, and 1.41% mIoU on the three datasets,
respectively.
