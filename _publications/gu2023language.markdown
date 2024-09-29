---
layout: publication
title: Seer Language Instructed Video Prediction With Latent Diffusion Models
authors: Gu Xianfan, Wen Chuan, Ye Weirui, Song Jiaming, Gao Yang
conference: "Arxiv"
year: 2023
bibkey: gu2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.14897"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Merging', 'Model Architecture', 'RAG', 'Tools']
---
Imagining the future trajectory is the key for robots to make sound planning and successfully reach their goals. Therefore text45;conditioned video prediction (TVP) is an essential task to facilitate general robot policy learning. To tackle this task and empower robots with the ability to foresee the future we propose a sample and computation45;efficient model named textbf123;Seer125; by inflating the pretrained text45;to45;image (T2I) stable diffusion models along the temporal axis. We enhance the U45;Net and language conditioning model by incorporating computation45;efficient spatial45;temporal attention. Furthermore we introduce a novel Frame Sequential Text Decomposer module that dissects a sentences global instruction into temporally aligned sub45;instructions ensuring precise integration into each frame of generation. Our framework allows us to effectively leverage the extensive prior knowledge embedded in pretrained T2I models across the frames. With the adaptable45;designed architecture Seer makes it possible to generate high45;fidelity coherent and instruction45;aligned video frames by fine45;tuning a few layers on a small amount of data. The experimental results on Something Something V2 (SSv2) Bridgedata and EpicKitchens45;100 datasets demonstrate our superior video prediction performance with around 48045;GPU hours versus CogVideo with over 1248045;GPU hours achieving the 3137; FVD improvement compared to the current SOTA model on SSv2 and 83.737; average preference in the human evaluation.
