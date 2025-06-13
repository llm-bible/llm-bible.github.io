---
layout: publication
title: 'Scalable Best-of-n Selection For Large Language Models Via Self-certainty'
authors: Zhewei Kang, Xuandong Zhao, Dawn Song
conference: "Arxiv"
year: 2025
bibkey: kang2025scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18581'}
  - {name: "Code", url: 'https://github.com/backprop07/Self-Certainty'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code']
---
Best-of-N selection is a key technique for improving the reasoning
performance of Large Language Models (LLMs) through increased test-time
computation. Current state-of-the-art methods often employ computationally
intensive reward models for response evaluation and selection. Reward-free
alternatives, like self-consistency and universal self-consistency, are limited
in their ability to handle open-ended generation tasks or scale effectively. To
address these limitations, we propose self-certainty, a novel and efficient
metric that leverages the inherent probability distribution of LLM outputs to
estimate response quality without requiring external reward models. We
hypothesize that higher distributional self-certainty, aggregated across
multiple samples, correlates with improved response accuracy, as it reflects
greater confidence in the generated output. Through extensive experiments on
various reasoning tasks, we demonstrate that self-certainty (1) scales
effectively with increasing sample size \\(N\\), akin to reward models but without
the computational overhead; (2) complements chain-of-thought, improving
reasoning performance beyond greedy decoding; and (3) generalizes to open-ended
tasks where traditional self-consistency methods fall short. Our findings
establish self-certainty as a practical and efficient way for improving LLM
reasoning capabilities. The code is available at
https://github.com/backprop07/Self-Certainty
