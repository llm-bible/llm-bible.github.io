---
layout: publication
title: 'QLIP: Text-aligned Visual Tokenization Unifies Auto-regressive Multimodal Understanding And Generation'
authors: Yue Zhao, Fuzhao Xue, Scott Reed, Linxi Fan, Yuke Zhu, Jan Kautz, Zhiding Yu, Philipp Krähenbühl, De-an Huang
conference: "Arxiv"
year: 2025
bibkey: zhao2025text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05178"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'Multimodal Models', 'Quantization']
---
We introduce Quantized Language-Image Pretraining (QLIP), a visual
tokenization method that combines state-of-the-art reconstruction quality with
state-of-the-art zero-shot image understanding. QLIP trains a
binary-spherical-quantization-based autoencoder with reconstruction and
language-image alignment objectives. We are the first to show that the two
objectives do not need to be at odds. We balance the two loss terms dynamically
during training and show that a two-stage training pipeline effectively mixes
the large-batch requirements of image-language pre-training with the memory
bottleneck imposed by the reconstruction objective. We validate the
effectiveness of QLIP for multimodal understanding and text-conditioned image
generation with a single model. Specifically, QLIP serves as a drop-in
replacement for the visual encoder for LLaVA and the image tokenizer for
LlamaGen with comparable or even better performance. Finally, we demonstrate
that QLIP enables a unified mixed-modality auto-regressive model for
understanding and generation.
