---
layout: publication
title: 'Seeking To Collide: Online Safety-critical Scenario Generation For Autonomous Driving With Retrieval Augmented Large Language Models'
authors: Yuewen Mei, Tong Nie, Jian Sun, Ye Tian
conference: "Arxiv"
year: 2025
bibkey: mei2025seeking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00972"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Tools', 'RAG']
---
Simulation-based testing is crucial for validating autonomous vehicles (AVs),
yet existing scenario generation methods either overfit to common driving
patterns or operate in an offline, non-interactive manner that fails to expose
rare, safety-critical corner cases. In this paper, we introduce an online,
retrieval-augmented large language model (LLM) framework for generating
safety-critical driving scenarios. Our method first employs an LLM-based
behavior analyzer to infer the most dangerous intent of the background vehicle
from the observed state, then queries additional LLM agents to synthesize
feasible adversarial trajectories. To mitigate catastrophic forgetting and
accelerate adaptation, we augment the framework with a dynamic memorization and
retrieval bank of intent-planner pairs, automatically expanding its behavioral
library when novel intents arise. Evaluations using the Waymo Open Motion
Dataset demonstrate that our model reduces the mean minimum time-to-collision
from 1.62 to 1.08 s and incurs a 75% collision rate, substantially
outperforming baselines.
