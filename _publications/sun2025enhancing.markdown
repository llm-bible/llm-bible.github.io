---
layout: publication
title: 'Causalabstain: Enhancing Multilingual Llms With Causal Reasoning For Trustworthy Abstention'
authors: Yuxi Sun, Aoqi Zuo, Wei Gao, Jing Ma
conference: "Arxiv"
year: 2025
bibkey: sun2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00519"}
  - {name: "Code", url: "https://github.com/peachch/CausalAbstain"}
tags: ['Ethics and Bias', 'RAG', 'Has Code', 'Interpretability and Explainability']
---
Large Language Models (LLMs) often exhibit knowledge disparities across languages. Encouraging LLMs to \textit\{abstain\} when faced with knowledge gaps is a promising strategy to reduce hallucinations in multilingual settings. Current abstention strategies for multilingual scenarios primarily rely on generating feedback in various languages using LLMs and performing self-reflection. However, these methods can be adversely impacted by inaccuracies and biases in the generated feedback. To address this, from a causal perspective, we introduce \textit\{CausalAbstain\}, a method that helps LLMs determine whether to utilize multiple generated feedback responses and how to identify the most useful ones. Extensive experiments demonstrate that \textit\{CausalAbstain\} effectively selects helpful feedback and enhances abstention decisions with interpretability in both native language (\textsc\{Casual-native\}) and multilingual (\textsc\{Causal-multi\}) settings, outperforming strong baselines on two benchmark datasets covering encyclopedic and commonsense knowledge QA tasks. Our code and data are open-sourced at https://github.com/peachch/CausalAbstain.
