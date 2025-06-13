---
layout: publication
title: 'Segment-level Diffusion: A Framework For Controllable Long-form Generation With Diffusion Language Models'
authors: Xiaochen Zhu, Georgi Karadzhov, Chenxi Whitehouse, Andreas Vlachos
conference: "Arxiv"
year: 2024
bibkey: zhu2024segment
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11333"}
tags: ['Tools', 'GPT', 'Applications', 'Language Modeling', 'Merging', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Diffusion models have shown promise in text generation, but often struggle with generating long, coherent, and contextually accurate text. Token-level diffusion doesn't model word-order dependencies explicitly and operates on short, fixed output windows, while passage-level diffusion struggles with learning robust representations for long-form text. To address these challenges, we propose Segment-Level Diffusion (SLD), a framework that enhances diffusion-based text generation through text segmentation, robust representation training with adversarial and contrastive learning, and improved latent-space guidance. By segmenting long-form outputs into multiple latent representations and decoding them with an autoregressive decoder, SLD simplifies diffusion predictions and improves scalability. Experiments on four datasets demonstrate that, when compared to other diffusion and autoregressive baselines SLD achieves competitive or superior fluency, coherence, and contextual compatibility in automatic and human evaluations.
