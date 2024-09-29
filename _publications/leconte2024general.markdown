---
layout: publication
title: Reallm A General Framework For LLM Compression And Fine45;tuning
authors: Leconte Louis, Bedin Lisa, Nguyen Van Minh, Moulines Eric
conference: "Arxiv"
year: 2024
bibkey: leconte2024general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13155"}
tags: ['Efficiency And Optimization', 'Quantization', 'Tools', 'Training Techniques']
---
We introduce ReALLM a novel approach for compression and memory45;efficient adaptation of pre45;trained language models that encompasses most of the post45;training quantization and fine45;tuning methods for a budget of <4 bits. Pre45;trained matrices are decomposed into a high45;precision low45;rank component and a vector45;quantized latent representation (using an autoencoder). During the fine45;tuning step only the low45;rank components are updated. Our results show that pre45;trained matrices exhibit different patterns. ReALLM adapts the shape of the encoder (small/large embedding high/low bit VQ etc.) to each matrix. ReALLM proposes to represent each matrix with a small embedding on b bits and a neural decoder model mathcal123;D125;95;φ with its weights on b95;φ bits. The decompression of a matrix requires only one embedding and a single forward pass with the decoder. Our weight45;only quantization algorithm yields the best results on language generation tasks (C4 and WikiText45;2) for a budget of 3 bits without any training. With a budget of 2 bits ReALLM achieves state45;of45;the art performance after fine45;tuning on a small calibration dataset.
