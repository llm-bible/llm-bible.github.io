---
layout: publication
title: KOALA Enhancing Speculative Decoding For LLM Via Multi-layer Draft Heads With Adversarial Learning
authors: Zhang Kaiqi, Zhao Jing, Chen Rui
conference: "Arxiv"
year: 2024
bibkey: zhang2024koala
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08146"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) exhibit high inference latency due to their autoregressive decoding nature. While the draft head in speculative decoding mitigates this issue its full potential remains unexplored. In this paper we introduce KOALA (K-layer Optimized Adversarial Learning Architecture) an orthogonal approach to the draft head. By transforming the conventional single-layer draft head into a multi-layer architecture and incorporating adversarial learning into the traditional supervised training KOALA significantly improves the accuracy of the draft head in predicting subsequent tokens thus more closely mirroring the functionality of LLMs. Although this improvement comes at the cost of slightly increased drafting overhead KOALA substantially unlocks the draft heads potential greatly enhancing speculative decoding. We conducted comprehensive evaluations of KOALA including both autoregressive and non-autoregressive draft heads across various tasks demonstrating a latency speedup ratio improvement of 0.24x-0.41x which is 10.5737;-14.0937; faster than the original draft heads.
