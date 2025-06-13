---
layout: publication
title: 'VILA-U: A Unified Foundation Model Integrating Visual Understanding And Generation'
authors: Yecheng Wu, Zhuoyang Zhang, Junyu Chen, Haotian Tang, Dacheng Li, Yunhao Fang, Ligeng Zhu, Enze Xie, Hongxu Yin, Li Yi, Song Han, Yao Lu
conference: "Arxiv"
year: 2024
bibkey: wu2024vila
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.04429'}
tags: ['Training Techniques', 'Tools', 'GPT', 'Merging', 'Pretraining Methods']
---
VILA-U is a Unified foundation model that integrates Video, Image, Language
understanding and generation. Traditional visual language models (VLMs) use
separate modules for understanding and generating visual content, which can
lead to misalignment and increased complexity. In contrast, VILA-U employs a
single autoregressive next-token prediction framework for both tasks,
eliminating the need for additional components like diffusion models. This
approach not only simplifies the model but also achieves near state-of-the-art
performance in visual language understanding and generation. The success of
VILA-U is attributed to two main factors: the unified vision tower that aligns
discrete visual tokens with textual inputs during pretraining, which enhances
visual perception, and autoregressive image generation can achieve similar
quality as diffusion models with high-quality dataset. This allows VILA-U to
perform comparably to more complex models using a fully token-based
autoregressive framework.
