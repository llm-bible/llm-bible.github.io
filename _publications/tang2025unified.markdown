---
layout: publication
title: 'Ugen: Unified Autoregressive Multimodal Model With Progressive Vocabulary Learning'
authors: Hongxuan Tang, Hao Liu, Xinyan Xiao
conference: "Arxiv"
year: 2025
bibkey: tang2025unified
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.21193'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Multimodal Models', 'Pretraining Methods']
---
We introduce UGen, a unified autoregressive multimodal model that
demonstrates strong performance across text processing, image understanding,
and image generation tasks simultaneously. UGen converts both texts and images
into discrete token sequences and utilizes a single transformer to generate
them uniformly in an autoregressive manner. To address the challenges
associated with unified multimodal learning, UGen is trained using a novel
mechanism, namely progressive vocabulary learning. In this process, visual
token IDs are incrementally activated and integrated into the training phase,
ultimately enhancing the effectiveness of unified multimodal learning.
Experiments on comprehensive text and image tasks show that UGen achieves a
significant overall performance improvement of 13.3% compared to the vanilla
unified autoregressive method, and it also delivers competitive results across
all tasks against several task-specific models.
