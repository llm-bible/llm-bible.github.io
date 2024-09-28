---
layout: publication
title: ReALLM A general framework for LLM compression and fine-tuning
authors: Leconte Louis, Bedin Lisa, Nguyen Van Minh, Moulines Eric
conference: "Arxiv"
year: 2024
bibkey: leconte2024reallm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13155"}
tags: ['Arxiv', 'LLM', 'A', 'Pretraining Methods', 'Quantization']
---
We introduce ReALLM a novel approach for compression and memory-efficient adaptation of pre-trained language models that encompasses most of the post-training quantization and fine-tuning methods for a budget of <4 bits. Pre-trained matrices are decomposed into a high-precision low-rank component and a vector-quantized latent representation (using an autoencoder). During the fine-tuning step only the low-rank components are updated. Our results show that pre-trained matrices exhibit different patterns. ReALLM adapts the shape of the encoder (small/large embedding high/low bit VQ etc.) to each matrix. ReALLM proposes to represent each matrix with a small embedding on b bits and a neural decoder model _phi with its weights on b_phi bits. The decompression of a matrix requires only one embedding and a single forward pass with the decoder. Our weight-only quantization algorithm yields the best results on language generation tasks (C4 and WikiText-2) for a budget of 3 bits without any training. With a budget of 2 bits ReALLM achieves state-of-the art performance after fine-tuning on a small calibration dataset.
