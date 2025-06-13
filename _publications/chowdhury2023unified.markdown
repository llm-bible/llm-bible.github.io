---
layout: publication
title: 'Apollo: Unified Adapter And Prompt Learning For Vision Language Models'
authors: Sanjoy Chowdhury, Sayan Nag, Dinesh Manocha
conference: "Arxiv"
year: 2023
bibkey: chowdhury2023unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01564"}
tags: ['Model Architecture', 'Attention Mechanism', 'Few-Shot', 'Multimodal Models', 'Prompting']
---
The choice of input text prompt plays a critical role in the performance of
Vision-Language Pretrained (VLP) models such as CLIP. We present APoLLo, a
unified multi-modal approach that combines Adapter and Prompt learning for
Vision-Language models. Our method is designed to substantially improve the
generalization capabilities of VLP models when they are fine-tuned in a
few-shot setting. We introduce trainable cross-attention-based adapter layers
in conjunction with vision and language encoders to strengthen the alignment
between the two modalities. We enforce consistency between the respective
encoder branches (receiving augmented inputs) to prevent overfitting in
downstream tasks. Our method is evaluated on three representative tasks:
generalization to novel classes, cross-dataset evaluation, and unseen domain
shifts. In practice, APoLLo achieves a relative gain up to 6.03% over MaPLe
(SOTA) on novel classes for 10 diverse image recognition datasets.
