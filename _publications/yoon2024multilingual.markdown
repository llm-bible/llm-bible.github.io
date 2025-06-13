---
layout: publication
title: 'Langbridge: Multilingual Reasoning Without Multilingual Supervision'
authors: Dongkeun Yoon, Joel Jang, Sungdong Kim, Seungone Kim, Sheikh Shafayat, Minjoon Seo
conference: "Arxiv"
year: 2024
bibkey: yoon2024multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.10695'}
tags: ['Training Techniques']
---
We introduce LangBridge, a zero-shot approach to adapt language models for
multilingual reasoning tasks without multilingual supervision. LangBridge
operates by bridging two models, each specialized in different aspects: (1) one
specialized in understanding multiple languages (e.g., mT5 encoder) and (2) one
specialized in reasoning (e.g., MetaMath). LangBridge connects the two models
by introducing minimal trainable parameters between them. Despite utilizing
only English data for training, LangBridge considerably enhances the
performance of language models on low-resource languages across mathematical
reasoning, code completion, logical reasoning, and commonsense reasoning. Our
analysis suggests that the efficacy of LangBridge stems from the
language-agnostic characteristics of multilingual representations. We publicly
release our code and models.
