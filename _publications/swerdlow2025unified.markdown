---
layout: publication
title: 'Unified Multimodal Discrete Diffusion'
authors: Alexander Swerdlow, Mihir Prabhudesai, Siddharth Gandhi, Deepak Pathak, Katerina Fragkiadaki
conference: "Arxiv"
year: 2025
bibkey: swerdlow2025unified
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.20853'}
  - {name: "Code", url: 'https://unidisc.github.io'}
tags: ['Has Code', 'Language Modeling', 'RAG', 'GPT', 'Applications', 'Merging', 'Multimodal Models', 'Pretraining Methods']
---
Multimodal generative models that can understand and generate across multiple
modalities are dominated by autoregressive (AR) approaches, which process
tokens sequentially from left to right, or top to bottom. These models jointly
handle images, text, video, and audio for various tasks such as image
captioning, question answering, and image generation. In this work, we explore
discrete diffusion models as a unified generative formulation in the joint text
and image domain, building upon their recent success in text generation.
Discrete diffusion models offer several advantages over AR models, including
improved control over quality versus diversity of generated samples, the
ability to perform joint multimodal inpainting (across both text and image
domains), and greater controllability in generation through guidance.
Leveraging these benefits, we present the first Unified Multimodal Discrete
Diffusion (UniDisc) model which is capable of jointly understanding and
generating text and images for a variety of downstream tasks. We compare
UniDisc to multimodal AR models, performing a scaling analysis and
demonstrating that UniDisc outperforms them in terms of both performance and
inference-time compute, enhanced controllability, editability, inpainting, and
flexible trade-off between inference time and generation quality. Code and
additional visualizations are available at https://unidisc.github.io.
