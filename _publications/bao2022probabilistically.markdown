---
layout: publication
title: P$^3$LM&#58; Probabilistically Permuted Prophet Language Modeling For Generative Pre-training
authors: Bao Junwei, Wang Yifan, Ying Jiangyong, Gong Yeyun, Zhao Jing, Wu Youzheng, He Xiaodong
conference: "Arxiv"
year: 2022
bibkey: bao2022probabilistically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.12339"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Conventional autoregressive left-to-right (L2R) sequence generation faces two issues during decoding limited to unidirectional target sequence modeling and constrained on strong local dependencies. To address the aforementioned problem we propose P^3LM a probabilistically permuted prophet language model which strengthens the modeling of bidirectional information and long token dependencies for sequence generation. Specifically P^3LM learns to generate tokens in permuted order upon an order-aware transformer decoder as well as to generate the corresponding future N tokens with a multi-stream attention mechanism. Extensive experiments are conducted on the GLGE benchmark which includes four datasets for summarization two for question generation one for conversational question answering and one for dialog response generation where P^3LM achieves state-of-the-art results compared with strong publicly available generative pre-training methods.
