---
layout: publication
title: 'Simda: Simple Diffusion Adapter For Efficient Video Generation'
authors: Zhen Xing, Qi Dai, Han Hu, Zuxuan Wu, Yu-gang Jiang
conference: "Arxiv"
year: 2023
bibkey: xing2023simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09710"}
tags: ['Fine-Tuning', 'Model Architecture', 'Merging', 'Training Techniques', 'Attention Mechanism']
---
The recent wave of AI-generated content has witnessed the great development
and success of Text-to-Image (T2I) technologies. By contrast, Text-to-Video
(T2V) still falls short of expectations though attracting increasing interests.
Existing works either train from scratch or adapt large T2I model to videos,
both of which are computation and resource expensive. In this work, we propose
a Simple Diffusion Adapter (SimDA) that fine-tunes only 24M out of 1.1B
parameters of a strong T2I model, adapting it to video generation in a
parameter-efficient way. In particular, we turn the T2I model for T2V by
designing light-weight spatial and temporal adapters for transfer learning.
Besides, we change the original spatial attention to the proposed Latent-Shift
Attention (LSA) for temporal consistency. With similar model architecture, we
further train a video super-resolution model to generate high-definition
(1024x1024) videos. In addition to T2V generation in the wild, SimDA could also
be utilized in one-shot video editing with only 2 minutes tuning. Doing so, our
method could minimize the training effort with extremely few tunable parameters
for model adaptation.
