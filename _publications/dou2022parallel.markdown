---
layout: publication
title: Parallel Attention Forcing For Machine Translation
authors: Dou Qingyun, Gales Mark
conference: "Arxiv"
year: 2022
bibkey: dou2022parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.03237"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Attention45;based autoregressive models have achieved state45;of45;the45;art performance in various sequence45;to45;sequence tasks including Text45;To45;Speech (TTS) and Neural Machine Translation (NMT) but can be difficult to train. The standard training approach teacher forcing guides a model with the reference back45;history. During inference the generated back45;history must be used. This mismatch limits the evaluation performance. Attention forcing has been introduced to address the mismatch guiding the model with the generated back45;history and reference attention. While successful in tasks with continuous outputs like TTS attention forcing faces additional challenges in tasks with discrete outputs like NMT. This paper introduces the two extensions of attention forcing to tackle these challenges. (1) Scheduled attention forcing automatically turns attention forcing on and off which is essential for tasks with discrete outputs. (2) Parallel attention forcing makes training parallel and is applicable to Transformer45;based models. The experiments show that the proposed approaches improve the performance of models based on RNNs and Transformers.
