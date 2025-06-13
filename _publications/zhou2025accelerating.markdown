---
layout: publication
title: 'Accelerating Unbiased LLM Evaluation Via Synthetic Feedback'
authors: Zhaoyi Zhou, Yuda Song, Andrea Zanette
conference: "Arxiv"
year: 2025
bibkey: zhou2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10563"}
tags: ['Ethics and Bias', 'Tools', 'Reinforcement Learning']
---
When developing new large language models (LLMs), a key step is evaluating
their final performance, often by computing the win-rate against a reference
model based on external feedback. Human feedback is the gold standard,
particularly for capturing nuanced qualities like coherence, readability, and
alignment with human expectations. However, human evaluations are costly --
even for large tech companies -- and when conducted with active users, they may
negatively impact user experience. A promising alternative is synthetic
feedback, where evaluations are conducted by other large language models,
including reward models. While this eliminates the need for costly human
annotations, it introduces biases that may distort the evaluation process. In
this work, we propose a statistically principled framework that integrates
human and synthetic feedback to reduce reliance on human annotations while
maintaining unbiased win-rate calculations. Our experiments demonstrate a
reduction in human annotations by up to 12.2% with an off-the-shelf synthetic
evaluator and up to 24.8% with a finetuned variant. Apart from being
generalizable, scalable, and free of hyper-parameter tuning, our method offers
predictable annotation savings, which can be estimated based on data-dependent
characteristics.
