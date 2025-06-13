---
layout: publication
title: 'Dualtoken: Towards Unifying Visual Understanding And Generation With Dual Visual Vocabularies'
authors: Wei Song, Yuran Wang, Zijia Song, Yadong Li, Haoze Sun, Weipeng Chen, Zenan Zhou, Jianhua Xu, Jiaqi Wang, Kaicheng Yu
conference: "Arxiv"
year: 2025
bibkey: song2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.14324'}
tags: ['GPT', 'Pretraining Methods']
---
The differing representation spaces required for visual understanding and
generation pose a challenge in unifying them within the autoregressive paradigm
of large language models. A vision tokenizer trained for reconstruction excels
at capturing low-level perceptual details, making it well-suited for visual
generation but lacking high-level semantic representations for understanding
tasks. Conversely, a vision encoder trained via contrastive learning aligns
well with language but struggles to decode back into the pixel space for
generation tasks. To bridge this gap, we propose DualToken, a method that
unifies representations for both understanding and generation within a single
tokenizer. However, directly integrating reconstruction and semantic objectives
in a single tokenizer creates conflicts, leading to degraded performance in
both reconstruction quality and semantic performance. Instead of forcing a
single codebook to handle both semantic and perceptual information, DualToken
disentangles them by introducing separate codebooks for high and low-level
features, effectively transforming their inherent conflict into a synergistic
relationship. As a result, DualToken achieves state-of-the-art performance in
both reconstruction and semantic tasks while demonstrating remarkable
effectiveness in downstream MLLM understanding and generation tasks. Notably,
we also show that DualToken, as a unified tokenizer, surpasses the naive
combination of two distinct types vision encoders, providing superior
performance within a unified MLLM.
