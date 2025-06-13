---
layout: publication
title: 'Training-free Regional Prompting For Diffusion Transformers'
authors: Anthony Chen, Jianjin Xu, Wenzhao Zheng, Gaole Dai, Yida Wang, Renrui Zhang, Haofan Wang, Shanghang Zhang
conference: "Arxiv"
year: 2024
bibkey: chen2024training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.02395'}
  - {name: "Code", url: 'https://github.com/antonioo-c/Regional-Prompting-FLUX'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Training Techniques', 'Model Architecture', 'Merging', 'Prompting', 'Pretraining Methods']
---
Diffusion models have demonstrated excellent capabilities in text-to-image
generation. Their semantic understanding (i.e., prompt following) ability has
also been greatly improved with large language models (e.g., T5, Llama).
However, existing models cannot perfectly handle long and complex text prompts,
especially when the text prompts contain various objects with numerous
attributes and interrelated spatial relationships. While many regional
prompting methods have been proposed for UNet-based models (SD1.5, SDXL), but
there are still no implementations based on the recent Diffusion Transformer
(DiT) architecture, such as SD3 and FLUX.1.In this report, we propose and
implement regional prompting for FLUX.1 based on attention manipulation, which
enables DiT with fined-grained compositional text-to-image generation
capability in a training-free manner. Code is available at
https://github.com/antonioo-c/Regional-Prompting-FLUX.
