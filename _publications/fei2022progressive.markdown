---
layout: publication
title: Progressive Text45;to45;image Generation
authors: Fei Zhengcong, Fan Mingyuan, Zhu Li, Huang Junshi
conference: "Arxiv"
year: 2022
bibkey: fei2022progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02291"}
tags: ['GPT', 'Pretraining Methods']
---
Recently Vector Quantized AutoRegressive (VQ45;AR) models have shown remarkable results in text45;to45;image synthesis by equally predicting discrete image tokens from the top left to bottom right in the latent space. Although the simple generative process surprisingly works well is this the best way to generate the image For instance human creation is more inclined to the outline45;to45;fine of an image while VQ45;AR models themselves do not consider any relative importance of image patches. In this paper we present a progressive model for high45;fidelity text45;to45;image generation. The proposed method takes effect by creating new image tokens from coarse to fine based on the existing context in a parallel manner and this procedure is recursively applied with the proposed error revision mechanism until an image sequence is completed. The resulting coarse45;to45;fine hierarchy makes the image generation process intuitive and interpretable. Extensive experiments in MS COCO benchmark demonstrate that the progressive model produces significantly better results compared with the previous VQ45;AR method in FID score across a wide variety of categories and aspects. Moreover the design of parallel generation in each step allows more than × 13 inference acceleration with slight performance loss.
