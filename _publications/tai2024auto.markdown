---
layout: publication
title: PIXAR Auto45;regressive Language Modeling In Pixel Space
authors: Tai Yintao, Liao Xiyang, Suglia Alessandro, Vergari Antonio
conference: "Arxiv"
year: 2024
bibkey: tai2024auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.03321"}
tags: ['Applications', 'BERT', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques']
---
Recent work showed the possibility of building open45;vocabulary large language models (LLMs) that directly operate on pixel representations. These models are implemented as autoencoders that reconstruct masked patches of rendered text. However these pixel45;based LLMs are limited to discriminative tasks (e.g. classification) and similar to BERT cannot be used to generate text. Therefore they cannot be used for generative tasks such as free45;form question answering. In this work we introduce PIXAR the first pixel45;based autoregressive LLM that performs text generation. Consisting of only a decoder PIXAR can perform free45;form generative tasks while keeping the number of parameters on par with previous encoder45;decoder models. Furthermore we highlight the challenges of generating text as non45;noisy images and show this is due to using a maximum likelihood objective. To overcome this problem we propose an adversarial pretraining stage that improves the readability and accuracy of PIXAR by 8.1 on LAMBADA and 8.5 on bAbI 45;45; making it comparable to GPT45;2 on text generation tasks. This paves the way to build open45;vocabulary LLMs that operate on perceptual input only and calls into question the necessity of the usual symbolic input representation i.e. text as (sub)tokens.
