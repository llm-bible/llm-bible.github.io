---
layout: publication
title: 'Speech-to-text Translation With Phoneme-augmented Cot: Enhancing Cross-lingual Transfer In Low-resource Scenarios'
authors: Gerard I. Gállego, Oriol Pareras, Martí Cortada Garcia, Lucas Takanori, Javier Hernando
conference: "Arxiv"
year: 2025
bibkey: gállego2025speech
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24691'}
tags: ['Tools', 'Training Techniques']
---
We propose a Speech-to-Text Translation (S2TT) approach that integrates phoneme representations into a Chain-of-Thought (CoT) framework to improve translation in low-resource and zero-resource settings. By introducing phoneme recognition as an intermediate step, we enhance cross-lingual transfer, enabling translation even for languages with no labeled speech data. Our system builds on a multilingual LLM, which we extend to process speech and phonemes. Training follows a curriculum learning strategy that progressively introduces more complex tasks. Experiments on multilingual S2TT benchmarks show that phoneme-augmented CoT improves translation quality in low-resource conditions and enables zero-resource translation, while slightly impacting high-resource performance. Despite this trade-off, our findings demonstrate that phoneme-based CoT is a promising step toward making S2TT more accessible across diverse languages.
