---
layout: publication
title: Video45;llama An Instruction45;tuned Audio45;visual Language Model For Video Understanding
authors: Zhang Hang, Li Xin, Bing Lidong
conference: "Arxiv"
year: 2023
bibkey: zhang2023video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.02858"}
tags: ['Applications', 'Language Modeling', 'RAG', 'Tools', 'Training Techniques']
---
We present Video45;LLaMA a multi45;modal framework that empowers Large Language Models (LLMs) with the capability of understanding both visual and auditory content in the video. Video45;LLaMA bootstraps cross45;modal training from the frozen pre45;trained visual and audio encoders and the frozen LLMs. Unlike previous works that complement LLMs to process the visual or audio signals only Video45;LLaMA enables video comprehension by tackling two challenges (1) capturing the temporal changes in visual scenes (2) integrating audio45;visual signals. To counter the first challenge we propose a Video Q45;former to assemble a pre45;trained image encoder into our video encoder and introduce a video45;to45;text generation task to learn video45;language correspondence. For the second challenge we leverage ImageBind a universal embedding model aligning multiple modalities as the pre45;trained audio encoder and introduce an Audio Q45;former on top of ImageBind to learn reasonable auditory query embeddings for the LLM module. To align the output of both visual and audio encoders with LLMs embedding space we first train Video45;LLaMA on massive video/image45;caption pairs and then tune our model with visual45;instruction datasets of moderate amount but higher quality. We found Video45;LLaMA shows the ability to perceive and comprehend video content and generate meaningful responses grounded in the visual and auditory information presented in the videos.
