---
layout: publication
title: 'Skewed Memorization In Large Language Models: Quantification And Decomposition'
authors: Hao Li, Di Huang, Ziyu Wang, Amir M. Rahmani
conference: "Arxiv"
year: 2025
bibkey: li2025skewed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01187"}
tags: ['Fine-Tuning', 'RAG', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Memorization in Large Language Models (LLMs) poses privacy and security
risks, as models may unintentionally reproduce sensitive or copyrighted data.
Existing analyses focus on average-case scenarios, often neglecting the highly
skewed distribution of memorization. This paper examines memorization in LLM
supervised fine-tuning (SFT), exploring its relationships with training
duration, dataset size, and inter-sample similarity. By analyzing memorization
probabilities over sequence lengths, we link this skewness to the token
generation process, offering insights for estimating memorization and comparing
it to established metrics. Through theoretical analysis and empirical
evaluation, we provide a comprehensive understanding of memorization behaviors
and propose strategies to detect and mitigate risks, contributing to more
privacy-preserving LLMs.
