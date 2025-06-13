---
layout: publication
title: 'Tapered Off-policy REINFORCE: Stable And Efficient Reinforcement Learning For Llms'
authors: Nicolas Le Roux, Marc G. Bellemare, Jonathan Lebensold, Arnaud Bergeron, Joshua Greaves, Alex Fréchette, Carolyne Pelletier, Eric Thibodeau-laufer, Sándor Toth, Sam Work
conference: "Arxiv"
year: 2025
bibkey: roux2025tapered
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14286"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
We propose a new algorithm for fine-tuning large language models using
reinforcement learning. Tapered Off-Policy REINFORCE (TOPR) uses an asymmetric,
tapered variant of importance sampling to speed up learning while maintaining
stable learning dynamics, even without the use of KL regularization. TOPR can
be applied in a fully offline fashion, allows the handling of positive and
negative examples in a unified framework, and benefits from the
implementational simplicity that is typical of Monte Carlo algorithms. We
demonstrate the effectiveness of our approach with a series of experiments on
the GSM8K and MATH reasoning benchmarks, finding performance gains for training
both a model for solution generation and as a generative verifier. We show that
properly leveraging positive and negative examples alike in the off-policy
regime simultaneously increases test-time accuracy and training data
efficiency, all the while avoiding the ``wasted inference'' that comes with
discarding negative examples. We find that this advantage persists over
multiple iterations of training and can be amplified by dataset curation
techniques, enabling us to match 70B-parameter model performance with 8B
language models. As a corollary to this work, we find that REINFORCE's baseline
parameter plays an important and unexpected role in defining dataset
composition in the presence of negative examples, and is consequently critical
in driving off-policy performance.
