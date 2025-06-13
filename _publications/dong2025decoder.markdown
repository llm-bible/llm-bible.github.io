---
layout: publication
title: 'Decoder-only Llms Are Better Controllers For Diffusion Models'
authors: Ziyi Dong, Yao Xiao, Pengxu Wei, Liang Lin
conference: "Arxiv"
year: 2025
bibkey: dong2025decoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04412"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Prompting']
---
Groundbreaking advancements in text-to-image generation have recently been
achieved with the emergence of diffusion models. These models exhibit a
remarkable ability to generate highly artistic and intricately detailed images
based on textual prompts. However, obtaining desired generation outcomes often
necessitates repetitive trials of manipulating text prompts just like casting
spells on a magic mirror, and the reason behind that is the limited capability
of semantic understanding inherent in current image generation models.
Specifically, existing diffusion models encode the text prompt input with a
pre-trained encoder structure, which is usually trained on a limited number of
image-caption pairs. The state-of-the-art large language models (LLMs) based on
the decoder-only structure have shown a powerful semantic understanding
capability as their architectures are more suitable for training on very
large-scale unlabeled data. In this work, we propose to enhance text-to-image
diffusion models by borrowing the strength of semantic understanding from large
language models, and devise a simple yet effective adapter to allow the
diffusion models to be compatible with the decoder-only structure. Meanwhile,
we also provide a supporting theoretical analysis with various architectures
(e.g., encoder-only, encoder-decoder, and decoder-only), and conduct extensive
empirical evaluations to verify its effectiveness. The experimental results
show that the enhanced models with our adapter module are superior to the
stat-of-the-art models in terms of text-to-image generation quality and
reliability.
