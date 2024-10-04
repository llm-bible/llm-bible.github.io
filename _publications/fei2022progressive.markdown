---
layout: publication
title: 'Progressive Text-to-image Generation'
authors: Fei Zhengcong, Fan Mingyuan, Zhu Li, Huang Junshi
conference: "Arxiv"
year: 2022
bibkey: fei2022progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02291"}
tags: ['GPT', 'Pretraining Methods']
---
Recently, Vector Quantized AutoRegressive (VQ-AR) models have shown remarkable results in text-to-image synthesis by equally predicting discrete image tokens from the top left to bottom right in the latent space. Although the simple generative process surprisingly works well, is this the best way to generate the image? For instance, human creation is more inclined to the outline-to-fine of an image, while VQ-AR models themselves do not consider any relative importance of image patches. In this paper, we present a progressive model for high-fidelity text-to-image generation. The proposed method takes effect by creating new image tokens from coarse to fine based on the existing context in a parallel manner, and this procedure is recursively applied with the proposed error revision mechanism until an image sequence is completed. The resulting coarse-to-fine hierarchy makes the image generation process intuitive and interpretable. Extensive experiments in MS COCO benchmark demonstrate that the progressive model produces significantly better results compared with the previous VQ-AR method in FID score across a wide variety of categories and aspects. Moreover, the design of parallel generation in each step allows more than \\(\times 13\\) inference acceleration with slight performance loss.
