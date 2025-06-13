---
layout: publication
title: 'Beneath The Surface: How Large Language Models Reflect Hidden Bias'
authors: Jinhao Pan, Chahat Raj, Ziyu Yao, Ziwei Zhu
conference: "Arxiv"
year: 2025
bibkey: pan2025beneath
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19749'}
  - {name: "Code", url: 'https://github.com/JP-25/Hidden-Bias-Benchmark'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Has Code', 'Training Techniques']
---
The exceptional performance of Large Language Models (LLMs) often comes with
the unintended propagation of social biases embedded in their training data.
While existing benchmarks evaluate overt bias through direct term associations
between bias concept terms and demographic terms, LLMs have become increasingly
adept at avoiding biased responses, creating an illusion of neutrality.
However, biases persist in subtler, contextually hidden forms that traditional
benchmarks fail to capture. We introduce the Hidden Bias Benchmark (HBB), a
novel dataset designed to assess hidden bias that bias concepts are hidden
within naturalistic, subtly framed contexts in real-world scenarios. We analyze
six state-of-the-art LLMs, revealing that while models reduce bias in response
to overt bias, they continue to reinforce biases in nuanced settings. Data,
code, and results are available at
https://github.com/JP-25/Hidden-Bias-Benchmark.
