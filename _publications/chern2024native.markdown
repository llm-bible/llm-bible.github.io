---
layout: publication
title: 'ANOLE: An Open, Autoregressive, Native Large Multimodal Models For Interleaved Image-text Generation'
authors: Ethan Chern, Jiadi Su, Yan Ma, Pengfei Liu
conference: "Arxiv"
year: 2024
bibkey: chern2024native
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06135"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Previous open-source large multimodal models (LMMs) have faced several
limitations: (1) they often lack native integration, requiring adapters to
align visual representations with pre-trained large language models (LLMs); (2)
many are restricted to single-modal generation; (3) while some support
multimodal generation, they rely on separate diffusion models for visual
modeling and generation. To mitigate these limitations, we present Anole, an
open, autoregressive, native large multimodal model for interleaved image-text
generation. We build Anole from Meta AI's Chameleon, adopting an innovative
fine-tuning strategy that is both data-efficient and parameter-efficient. Anole
demonstrates high-quality, coherent multimodal generation capabilities. We have
open-sourced our model, training framework, and instruction tuning data.
