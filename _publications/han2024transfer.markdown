---
layout: publication
title: 'Transfer Learning For Text Diffusion Models'
authors: Han Kehang, Kenealy Kathleen, Barua Aditya, Fiedel Noah, Constant Noah
conference: "Arxiv"
year: 2024
bibkey: han2024transfer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17181"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
In this report, we explore the potential for text diffusion to replace autoregressive (AR) decoding for the training and deployment of large language models (LLMs). We are particularly interested to see whether pretrained AR models can be transformed into text diffusion models through a lightweight adaptation procedure we call AR2Diff''. We begin by establishing a strong baseline setup for training text diffusion models. Comparing across multiple architectures and pretraining objectives, we find that training a decoder-only model with a prefix LM objective is best or near-best across several tasks. Building on this finding, we test various transfer learning setups for text diffusion models. On machine translation, we find that text diffusion underperforms the standard AR approach. However, on code synthesis and extractive QA, we find diffusion models trained from scratch outperform AR models in many cases. We also observe quality gains from AR2Diff -- adapting AR models to use diffusion decoding. These results are promising given that text diffusion is relatively underexplored and can be significantly faster than AR decoding for long text generation.
