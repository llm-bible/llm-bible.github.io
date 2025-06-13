---
layout: publication
title: 'Incentivizing Truthful Language Models Via Peer Elicitation Games'
authors: Baiting Chen, Tong Zhu, Jiale Han, Lexin Li, Gang Li, Xiaowu Dai
conference: "Arxiv"
year: 2025
bibkey: chen2025incentivizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13636"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated strong generative capabilities but remain prone to inconsistencies and hallucinations. We introduce Peer Elicitation Games (PEG), a training-free, game-theoretic framework for aligning LLMs through a peer elicitation mechanism involving a generator and multiple discriminators instantiated from distinct base models. Discriminators interact in a peer evaluation setting, where rewards are computed using a determinant-based mutual information score that provably incentivizes truthful reporting without requiring ground-truth labels. We establish theoretical guarantees showing that each agent, via online learning, achieves sublinear regret in the sense their cumulative performance approaches that of the best fixed truthful strategy in hindsight. Moreover, we prove last-iterate convergence to a truthful Nash equilibrium, ensuring that the actual policies used by agents converge to stable and truthful behavior over time. Empirical evaluations across multiple benchmarks demonstrate significant improvements in factual accuracy. These results position PEG as a practical approach for eliciting truthful behavior from LLMs without supervision or fine-tuning.
