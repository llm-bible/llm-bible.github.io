---
layout: publication
title: 'Lmfusion: Adapting Pretrained Language Models For Multimodal Generation'
authors: Weijia Shi, Xiaochuang Han, Chunting Zhou, Weixin Liang, Xi Victoria Lin, Luke Zettlemoyer, Lili Yu
conference: "Arxiv"
year: 2024
bibkey: shi2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15188"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Merging', 'GPT', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
We present LMFusion, a framework for empowering pretrained text-only large
language models (LLMs) with multimodal generative capabilities, enabling them
to understand and generate both text and images in arbitrary sequences.
LMFusion leverages existing Llama-3's weights for processing texts
autoregressively while introducing additional and parallel transformer modules
for processing images with diffusion. During training, the data from each
modality is routed to its dedicated modules: modality-specific feedforward
layers, query-key-value projections, and normalization layers process each
modality independently, while the shared self-attention layers allow
interactions across text and image features. By freezing the text-specific
modules and only training the image-specific modules, LMFusion preserves the
language capabilities of text-only LLMs while developing strong visual
understanding and generation abilities. Compared to methods that pretrain
multimodal generative models from scratch, our experiments demonstrate that,
LMFusion improves image understanding by 20% and image generation by 3.6% using
only 50% of the FLOPs while maintaining Llama-3's language capabilities. We
also demonstrate that this framework can adapt existing vision-language models
with multimodal generation ability. Overall, this framework not only leverages
existing computational investments in text-only LLMs but also enables the
parallel development of language and vision capabilities, presenting a
promising direction for efficient multimodal model development.
