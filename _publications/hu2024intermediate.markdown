---
layout: publication
title: An Intermediate Fusion Vit Enables Efficient Text45;image Alignment In Diffusion Models
authors: Hu Zizhao, Jia Shaochong, Rostami Mohammad
conference: "Arxiv"
year: 2024
bibkey: hu2024intermediate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16530"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Diffusion models have been widely used for conditional data cross45;modal generation tasks such as text45;to45;image and text45;to45;video. However state45;of45;the45;art models still fail to align the generated visual concepts with high45;level semantics in a language such as object count spatial relationship etc. We approach this problem from a multimodal data fusion perspective and investigate how different fusion strategies can affect vision45;language alignment. We discover that compared to the widely used early fusion of conditioning text in a pretrained image feature space a specially designed intermediate fusion can (i) boost text45;to45;image alignment with improved generation quality and (ii) improve training and inference efficiency by reducing low45;rank text45;to45;image attention calculations. We perform experiments using a text45;to45;image generation task on the MS45;COCO dataset. We compare our intermediate fusion mechanism with the classic early fusion mechanism on two common conditioning methods on a U45;shaped ViT backbone. Our intermediate fusion model achieves a higher CLIP Score and lower FID with 2037; reduced FLOPs and 5037; increased training speed compared to a strong U45;ViT baseline with an early fusion.
