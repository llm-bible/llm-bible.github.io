---
layout: publication
title: Metric-aware LLM inference for regression and scoring
authors: Lukasik Michal, Narasimhan Harikrishna, Menon Aditya Krishna, Yu Felix, Kumar Sanjiv
conference: "Arxiv"
year: 2024
bibkey: lukasik2024metric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04182"}
tags: ['ARXIV', 'LLM', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated strong results on a range of NLP tasks. Typically outputs are obtained via autoregressive sampling from the LLMs underlying distribution. Building on prior work on Minimum Bayes Risk Decoding we show that this inference strategy can be suboptimal for a range of regression and scoring tasks and associated evaluation metrics. As a remedy we propose metric aware LLM inference a decision theoretic approach optimizing for custom regression and scoring metrics at inference time. We report improvements over baselines on academic benchmarks and publicly available models.
