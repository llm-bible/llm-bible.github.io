---
layout: publication
title: On The Interchangeability Of Positional Embeddings In Multilingual Neural Machine Translation Models
authors: Gumma Varun, Chitale Pranjal A., Bali Kalika
conference: "Arxiv"
year: 2024
bibkey: gumma2024interchangeability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11382"}
tags: ['Applications', 'Efficiency And Optimization', 'Model Architecture']
---
Standard Neural Machine Translation (NMT) models have traditionally been trained with Sinusoidal Positional Embeddings (PEs) which are inadequate for capturing long45;range dependencies and are inefficient for long45;context or document45;level translation. In contrast state45;of45;the45;art large language models (LLMs) employ relative PEs demonstrating superior length generalization. This work explores the potential for efficiently switching the Positional Embeddings of pre45;trained NMT models from absolute sinusoidal PEs to relative approaches such as RoPE and ALiBi. Our findings reveal that sinusoidal PEs can be effectively replaced with RoPE and ALiBi with negligible or no performance loss achieved by fine45;tuning on a small fraction of high45;quality data. Additionally models trained without Positional Embeddings (NoPE) are not a viable solution for Encoder45;Decoder architectures as they consistently under45;perform compared to models utilizing any form of Positional Embedding. Furthermore even a model trained from scratch with these relative PEs slightly under45;performs a fine45;tuned model underscoring the efficiency and validity of our hypothesis.
