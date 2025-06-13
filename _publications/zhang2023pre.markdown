---
layout: publication
title: 'Pre-trained Language Models Do Not Help Auto-regressive Text-to-image Generation'
authors: Yuhui Zhang, Brandon Mckinzie, Zhe Gan, Vaishaal Shankar, Alexander Toshev
conference: "Arxiv"
year: 2023
bibkey: zhang2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16201"}
tags: ['Pre-Training', 'Interpretability and Explainability', 'RAG', 'Training Techniques', 'Multimodal Models']
---
Recent advances in image tokenizers, such as VQ-VAE, have enabled
text-to-image generation using auto-regressive methods, similar to language
modeling. However, these methods have yet to leverage pre-trained language
models, despite their adaptability to various downstream tasks. In this work,
we explore this gap by adapting a pre-trained language model for
auto-regressive text-to-image generation, and find that pre-trained language
models offer limited help. We provide a two-fold explanation by analyzing
tokens from each modality. First, we demonstrate that image tokens possess
significantly different semantics compared to text tokens, rendering
pre-trained language models no more effective in modeling them than randomly
initialized ones. Second, the text tokens in the image-text datasets are too
simple compared to normal language model pre-training data, which causes the
catastrophic degradation of language models' capability.
