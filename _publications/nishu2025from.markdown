---
layout: publication
title: 'From Dense To Dynamic: Token-difficulty Driven Moefication Of Pre-trained Llms'
authors: Kumari Nishu, Sachin Mehta, Samira Abnar, Mehrdad Farajtabar, Maxwell Horton, Mahyar Najibi, Moin Nabi, Minsik Cho, Devang Naik
conference: "Arxiv"
year: 2025
bibkey: nishu2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12325'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Training large language models (LLMs) for different inference constraints is
computationally expensive, limiting control over efficiency-accuracy
trade-offs. Moreover, once trained, these models typically process tokens
uniformly, regardless of their complexity, leading to static and inflexible
behavior. In this paper, we introduce a post-training optimization framework,
DynaMoE, that adapts a pre-trained dense LLM to a token-difficulty-driven
Mixture-of-Experts model with minimal fine-tuning cost. This adaptation makes
the model dynamic, with sensitivity control to customize the balance between
efficiency and accuracy. DynaMoE features a token-difficulty-aware router that
predicts the difficulty of tokens and directs them to the appropriate
sub-networks or experts, enabling larger experts to handle more complex tokens
and smaller experts to process simpler ones. Our experiments demonstrate that
DynaMoE can generate a range of adaptive model variants of the existing trained
LLM with a single fine-tuning step, utilizing only \\(10B\\) tokens, a minimal cost
compared to the base model's training. Each variant offers distinct trade-offs
between accuracy and performance. Compared to the baseline post-training
optimization framework, Flextron, our method achieves similar aggregated
accuracy across downstream tasks, despite using only \\(\frac\{1\}\{9\}\text\{th\}\\) of
their fine-tuning cost.
