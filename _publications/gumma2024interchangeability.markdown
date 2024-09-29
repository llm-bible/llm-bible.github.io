---
layout: publication
title: "On The Interchangeability Of Positional Embeddings In Multilingual Neural Machine Translation Models"
authors: Gumma Varun, Chitale Pranjal A., Bali Kalika
conference: "Arxiv"
year: 2024
bibkey: gumma2024interchangeability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11382"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Standard Neural Machine Translation (NMT) models have traditionally been trained with Sinusoidal Positional Embeddings (PEs) which are inadequate for capturing long-range dependencies and are inefficient for long-context or document-level translation. In contrast state-of-the-art large language models (LLMs) employ relative PEs demonstrating superior length generalization. This work explores the potential for efficiently switching the Positional Embeddings of pre-trained NMT models from absolute sinusoidal PEs to relative approaches such as RoPE and ALiBi. Our findings reveal that sinusoidal PEs can be effectively replaced with RoPE and ALiBi with negligible or no performance loss achieved by fine-tuning on a small fraction of high-quality data. Additionally models trained without Positional Embeddings (NoPE) are not a viable solution for Encoder-Decoder architectures as they consistently under-perform compared to models utilizing any form of Positional Embedding. Furthermore even a model trained from scratch with these relative PEs slightly under-performs a fine-tuned model underscoring the efficiency and validity of our hypothesis.
