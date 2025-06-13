---
layout: publication
title: 'Generalising From Self-produced Data: Model Training Beyond Human Constraints'
authors: Alfath Daryl Alhajir, Jennifer Dodgson, Joseph Lim, Truong Ma Phi, Julian Peh, Akira Rafhael Janson Pattirane, Lokesh Poovaragan
conference: "Arxiv"
year: 2025
bibkey: alhajir2025generalising
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04711'}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Current large language models (LLMs) are constrained by human-derived
training data and limited by a single level of abstraction that impedes
definitive truth judgments. This paper introduces a novel framework in which AI
models autonomously generate and validate new knowledge through direct
interaction with their environment. Central to this approach is an unbounded,
ungamable numeric reward - such as annexed disk space or follower count - that
guides learning without requiring human benchmarks. AI agents iteratively
generate strategies and executable code to maximize this metric, with
successful outcomes forming the basis for self-retraining and incremental
generalisation. To mitigate model collapse and the warm start problem, the
framework emphasizes empirical validation over textual similarity and supports
fine-tuning via GRPO. The system architecture employs modular agents for
environment analysis, strategy generation, and code synthesis, enabling
scalable experimentation. This work outlines a pathway toward self-improving AI
systems capable of advancing beyond human-imposed constraints toward autonomous
general intelligence.
