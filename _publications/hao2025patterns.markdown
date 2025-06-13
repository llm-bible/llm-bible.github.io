---
layout: publication
title: 'Patterns And Mechanisms Of Contrastive Activation Engineering'
authors: Yixiong Hao, Ayush Panda, Stepan Shabalin, Sheikh Abdur Raheem Ali
conference: "Arxiv"
year: 2025
bibkey: hao2025patterns
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03189'}
tags: ['Fine-Tuning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Controlling the behavior of Large Language Models (LLMs) remains a
significant challenge due to their inherent complexity and opacity. While
techniques like fine-tuning can modify model behavior, they typically require
extensive computational resources. Recent work has introduced a class of
contrastive activation engineering (CAE) techniques as promising approaches for
steering LLM outputs through targeted modifications to their internal
representations. Applied at inference-time with zero cost, CAE has the
potential to introduce a new paradigm of flexible, task-specific LLM behavior
tuning. We analyze the performance of CAE in in-distribution,
out-of-distribution settings, evaluate drawbacks, and begin to develop
comprehensive guidelines for its effective deployment. We find that 1. CAE is
only reliably effective when applied to in-distribution contexts. 2. Increasing
the number of samples used to generate steering vectors has diminishing returns
at around 80 samples. 3. Steering vectors are susceptible to adversarial inputs
that reverses the behavior that is steered for. 4. Steering vectors harm the
overall model perplexity. 5. Larger models are more resistant to
steering-induced degradation.
