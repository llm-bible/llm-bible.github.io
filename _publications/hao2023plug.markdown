---
layout: publication
title: Vico Plug45;and45;play Visual Condition For Personalized Text45;to45;image Generation
authors: Hao Shaozhe, Han Kai, Zhao Shihao, Wong Kwan-yee K.
conference: "Arxiv"
year: 2023
bibkey: hao2023plug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00971"}
  - {name: "Code", url: "https://github.com/haoosz/ViCo"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Training Techniques']
---
Personalized text45;to45;image generation using diffusion models has recently emerged and garnered significant interest. This task learns a novel concept (e.g. a unique toy) illustrated in a handful of images into a generative model that captures fine visual details and generates photorealistic images based on textual embeddings. In this paper we present ViCo a novel lightweight plug45;and45;play method that seamlessly integrates visual condition into personalized text45;to45;image generation. ViCo stands out for its unique feature of not requiring any fine45;tuning of the original diffusion model parameters thereby facilitating more flexible and scalable model deployment. This key advantage distinguishes ViCo from most existing models that necessitate partial or full diffusion fine45;tuning. ViCo incorporates an image attention module that conditions the diffusion process on patch45;wise visual semantics and an attention45;based object mask that comes at no extra cost from the attention module. Despite only requiring light parameter training (~637; compared to the diffusion U45;Net) ViCo delivers performance that is on par with or even surpasses all state45;of45;the45;art models both qualitatively and quantitatively. This underscores the efficacy of ViCo making it a highly promising solution for personalized text45;to45;image generation without the need for diffusion model fine45;tuning. Code https://github.com/haoosz/ViCo
