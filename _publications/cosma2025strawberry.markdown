---
layout: publication
title: 'The Strawberry Problem: Emergence Of Character-level Understanding In Tokenized Language Models'
authors: Adrian Cosma, Stefan Ruseti, Emilian Radoi, Mihai Dascalu
conference: "Arxiv"
year: 2025
bibkey: cosma2025strawberry
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14172"}
tags: ['Training Techniques', 'Tokenization', 'Tools']
---
Despite their remarkable progress across diverse domains, Large Language Models (LLMs) consistently fail at simple character-level tasks, such as counting letters in words, due to a fundamental limitation: tokenization. In this work, we frame this limitation as a problem of low mutual information and analyze it in terms of concept emergence. Using a suite of 19 synthetic tasks that isolate character-level reasoning in a controlled setting, we show that such capabilities emerge slowly, suddenly, and only late in training. We further show that percolation-based models of concept emergence explain these patterns, suggesting that learning character composition is not fundamentally different from learning commonsense knowledge. To address this bottleneck, we propose a lightweight architectural modification that significantly improves character-level reasoning while preserving the inductive advantages of subword models. Together, our results bridge low-level perceptual gaps in tokenized LMs and provide a principled framework for understanding and mitigating their structural blind spots. We make our code publicly available.
