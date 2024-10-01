---
layout: publication
title: 'Grounded Compositional And Diverse Text-to-3d With Pretrained Multi-view Diffusion Model'
authors: Li Xiaolong, Mo Jiawei, Wang Ying, Parameshwara Chethan, Fei Xiaohan, Swaminathan Ashwin, Taylor Cj, Tu Zhuowen, Favaro Paolo, Soatto Stefano
conference: "Arxiv"
year: 2024
bibkey: li2024grounded
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18065"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Prompting', 'RAG']
---
In this paper, we propose an effective two-stage approach named Grounded-Dreamer to generate 3D assets that can accurately follow complex, compositional text prompts while achieving high fidelity by using a pre-trained multi-view diffusion model. Multi-view diffusion models, such as MVDream, have shown to generate high-fidelity 3D assets using score distillation sampling (SDS). However, applied naively, these methods often fail to comprehend compositional text prompts, and may often entirely omit certain subjects or parts. To address this issue, we first advocate leveraging text-guided 4-view images as the bottleneck in the text-to-3D pipeline. We then introduce an attention refocusing mechanism to encourage text-aligned 4-view image generation, without the necessity to re-train the multi-view diffusion model or craft a high-quality compositional 3D dataset. We further propose a hybrid optimization strategy to encourage synergy between the SDS loss and the sparse RGB reference images. Our method consistently outperforms previous state-of-the-art (SOTA) methods in generating compositional 3D assets, excelling in both quality and accuracy, and enabling diverse 3D from the same text prompt.
