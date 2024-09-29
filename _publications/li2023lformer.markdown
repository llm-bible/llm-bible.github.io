---
layout: publication
title: Lformer Text-to-Image Generation with L-shape Block Parallel Decoding
authors: Li Jiacheng, Wei Longhui, Zhan Zongyuan, He Xin, Tang Siliang, Tian Qi, Zhuang Yueting
conference: "Arxiv"
year: 2023
bibkey: li2023lformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.03800"}
tags: ['GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Generative transformers have shown their superiority in synthesizing high-fidelity and high-resolution images such as good diversity and training stability. However they suffer from the problem of slow generation since they need to generate a long token sequence autoregressively. To better accelerate the generative transformers while keeping good generation quality we propose Lformer a semi-autoregressive text-to-image generation model. Lformer firstly encodes an image into htimesh discrete tokens then divides these tokens into h mirrored L-shape blocks from the top left to the bottom right and decodes the tokens in a block parallelly in each step. Lformer predicts the area adjacent to the previous context like autoregressive models thus it is more stable while accelerating. By leveraging the 2D structure of image tokens Lformer achieves faster speed than the existing transformer-based methods while keeping good generation quality. Moreover the pretrained Lformer can edit images without the requirement for finetuning. We can roll back to the early steps for regeneration or edit the image with a bounding box and a text prompt.
