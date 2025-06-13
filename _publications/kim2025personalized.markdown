---
layout: publication
title: 'Personalized Language Models Via Privacy-preserving Evolutionary Model Merging'
authors: Kyuyoung Kim, Jinwoo Shin, Jaehyung Kim
conference: "Arxiv"
year: 2025
bibkey: kim2025personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18008"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Prompting', 'Merging']
---
Personalization in large language models (LLMs) seeks to tailor models to
individual user or user group preferences. Prompt-based methods augment queries
with user preference information, whereas training-based methods directly
encode preferences into model parameters for more effective personalization.
Despite achieving some success in personalizing LLMs, prior methods often fail
to directly optimize task-specific metrics and lack explicit
privacy-preservation mechanisms. To address these limitations, we propose
Privacy-Preserving Model Merging via Evolutionary Algorithms (PriME), a novel
approach to personalization that employs gradient-free methods to directly
optimize task-specific metrics while preserving user privacy. By incorporating
privacy preservation into optimization, PriME produces a personalized module
that effectively captures the target user's preferences while minimizing the
privacy risks for the users sharing their private information. Experiments on
the LaMP benchmark show that PriME outperforms both prompt-based and
training-based methods, achieving up to a 45% performance improvement over the
prior art. Further analysis shows that PriME achieves a significantly better
privacy-utility trade-off, highlighting the potential of evolutionary
approaches for privacy-preserving LLM personalization.
