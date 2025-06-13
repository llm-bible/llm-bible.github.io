---
layout: publication
title: 'Efficient Scaling Of Diffusion Transformers For Text-to-image Generation'
authors: Hao Li, Shamit Lal, Zhiheng Li, Yusheng Xie, Ying Wang, Yang Zou, Orchid Majumder, R. Manmatha, Zhuowen Tu, Stefano Ermon, Stefano Soatto, Ashwin Swaminathan
conference: "Arxiv"
year: 2024
bibkey: li2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12391"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Merging', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
We empirically study the scaling properties of various Diffusion Transformers
(DiTs) for text-to-image generation by performing extensive and rigorous
ablations, including training scaled DiTs ranging from 0.3B upto 8B parameters
on datasets up to 600M images. We find that U-ViT, a pure self-attention based
DiT model provides a simpler design and scales more effectively in comparison
with cross-attention based DiT variants, which allows straightforward expansion
for extra conditions and other modalities. We identify a 2.3B U-ViT model can
get better performance than SDXL UNet and other DiT variants in controlled
setting. On the data scaling side, we investigate how increasing dataset size
and enhanced long caption improve the text-image alignment performance and the
learning efficiency.
