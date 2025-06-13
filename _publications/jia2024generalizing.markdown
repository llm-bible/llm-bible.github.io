---
layout: publication
title: 'Generalizing Reward Modeling For Out-of-distribution Preference Learning'
authors: Chen Jia
conference: "Arxiv"
year: 2024
bibkey: jia2024generalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14760"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'Applications']
---
Preference learning (PL) with large language models (LLMs) aims to align the
LLMs' generations with human preferences. Previous work on reinforcement
learning from human feedback (RLHF) has demonstrated promising results in
in-distribution PL. However, due to the difficulty of obtaining human feedback,
discretely training reward models for every encountered distribution is
challenging. Thus, out-of-distribution (OOD) PL is practically useful for
enhancing the generalization ability of LLMs with limited preference feedback.
This work addresses OOD PL by optimizing a general reward model through a
meta-learning approach. During meta-training, a bilevel optimization algorithm
is utilized to learn a reward model capable of guiding policy learning to align
with human preferences across various distributions. When encountering a test
distribution, the meta-test procedure conducts regularized policy optimization
using the learned reward model for PL. We theoretically demonstrate the
convergence rate of the bilevel optimization algorithm under reasonable
assumptions. Additionally, we conduct experiments on two text generation tasks
across 20 held-out domains and outperform a variety of strong baselines across
various evaluation metrics.
