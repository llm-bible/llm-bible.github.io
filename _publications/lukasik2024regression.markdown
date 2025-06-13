---
layout: publication
title: 'Regression-aware Inference With Llms'
authors: Michal Lukasik, Harikrishna Narasimhan, Aditya Krishna Menon, Felix Yu, Sanjiv Kumar
conference: "EMNLP Findings 2024"
year: 2024
bibkey: lukasik2024regression
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04182"}
tags: ['Pretraining Methods', 'GPT', 'Applications']
---
Large language models (LLMs) have shown strong results on a range of
applications, including regression and scoring tasks. Typically, one obtains
outputs from an LLM via autoregressive sampling from the model's output
distribution. We show that this inference strategy can be sub-optimal for
common regression and scoring evaluation metrics. As a remedy, we build on
prior work on Minimum Bayes Risk decoding, and propose alternate inference
strategies that estimate the Bayes-optimal solution for regression and scoring
metrics in closed-form from sampled responses. We show that our proposal
significantly improves over baselines across datasets and models.
