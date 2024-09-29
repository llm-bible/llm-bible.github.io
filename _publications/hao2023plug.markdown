---
layout: publication
title: Vico: Plug-and-play Visual Condition For Personalized Text-to-image Generation
authors: Hao Shaozhe, Han Kai, Zhao Shihao, Wong Kwan-yee K.
conference: "Arxiv"
year: 2023
bibkey: hao2023plug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00971"}
  - {name: "Code", url: "https://github.com/haoosz/ViCo"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Personalized text-to-image generation using diffusion models has recently emerged and garnered significant interest. This task learns a novel concept (e.g. a unique toy) illustrated in a handful of images into a generative model that captures fine visual details and generates photorealistic images based on textual embeddings. In this paper we present ViCo a novel lightweight plug-and-play method that seamlessly integrates visual condition into personalized text-to-image generation. ViCo stands out for its unique feature of not requiring any fine-tuning of the original diffusion model parameters thereby facilitating more flexible and scalable model deployment. This key advantage distinguishes ViCo from most existing models that necessitate partial or full diffusion fine-tuning. ViCo incorporates an image attention module that conditions the diffusion process on patch-wise visual semantics and an attention-based object mask that comes at no extra cost from the attention module. Despite only requiring light parameter training (~637; compared to the diffusion U-Net) ViCo delivers performance that is on par with or even surpasses all state-of-the-art models both qualitatively and quantitatively. This underscores the efficacy of ViCo making it a highly promising solution for personalized text-to-image generation without the need for diffusion model fine-tuning. Code https://github.com/haoosz/ViCo"
