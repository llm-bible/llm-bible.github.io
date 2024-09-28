---
layout: publication
title: Diffusion Glancing Transformer for Parallel Sequence to Sequence Learning
authors: Qian Lihua, Wang Mingxuan, Liu Yang, Zhou Hao
conference: "Arxiv"
year: 2022
bibkey: qian2022diffusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10240"}
tags: ['ARXIV', 'Language Modeling', 'Merging', 'Model Architecture', 'Transformer']
---
Previously non-autoregressive models were widely perceived as being superior in generation efficiency but inferior in generation quality due to the difficulties of modeling multiple target modalities. To enhance the multi-modality modeling ability we propose the diffusion glancing transformer which employs a modality diffusion process and residual glancing sampling. The modality diffusion process is a discrete process that interpolates the multi-modal distribution along the decoding steps and the residual glancing sampling approach guides the model to continuously learn the remaining modalities across the layers. Experimental results on various machine translation and text generation benchmarks demonstrate that DIFFGLAT achieves better generation accuracy while maintaining fast decoding speed compared with both autoregressive and non-autoregressive models.
