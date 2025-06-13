---
layout: publication
title: 'Vitoc: Vision Transformer And Object-aware Captioner'
authors: Feiyang Huang
conference: "Arxiv"
year: 2024
bibkey: huang2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.07265"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
This paper presents ViTOC (Vision Transformer and Object-aware Captioner), a
novel vision-language model for image captioning that addresses the challenges
of accuracy and diversity in generated descriptions. Unlike conventional
approaches, ViTOC employs a dual-path architecture based on Vision Transformer
and object detector, effectively fusing global visual features and local object
information through learnable vectors. The model introduces an innovative
object-aware prompting strategy that significantly enhances its capability in
handling long-tail data. Experiments on the standard COCO dataset demonstrate
that ViTOC outperforms baseline models across all evaluation metrics.
Additionally, we propose a reference-free evaluation method based on CLIP to
further validate the model's effectiveness. By utilizing pretrained visual
model parameters, ViTOC achieves efficient end-to-end training.
