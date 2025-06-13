---
layout: publication
title: 'Empower Nested Boolean Logic Via Self-supervised Curriculum Learning'
authors: Hongqiu Wu, Linfeng Liu, Hai Zhao, Min Zhang
conference: "Arxiv"
year: 2023
bibkey: wu2023empower
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05450"}
tags: ['Pretraining Methods', 'Training Techniques', 'Reinforcement Learning']
---
Beyond the great cognitive powers showcased by language models, it is crucial
to scrutinize whether their reasoning capabilities stem from strong
generalization or merely exposure to relevant data. As opposed to constructing
increasingly complex logic, this paper probes into the boolean logic, the root
capability of a logical reasoner. We find that any pre-trained language models
even including large language models only behave like a random selector in the
face of multi-nested boolean logic, a task that humans can handle with ease. To
empower language models with this fundamental capability, this paper proposes a
new self-supervised learning method \textit\{Curriculum Logical Reasoning\}
(\textsc\{Clr\}), where we augment the training data with nested boolean logic
chain step-by-step, and program the training from simpler logical patterns
gradually to harder ones. This new training paradigm allows language models to
effectively generalize to much harder and longer-hop logic, which can hardly be
learned through naive training. Furthermore, we show that boolean logic is a
great foundation for improving the subsequent general logical tasks.
