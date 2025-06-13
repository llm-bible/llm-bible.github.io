---
layout: publication
title: 'Retrieval Augmented Learning: A Retrial-based Large Language Model Self-supervised Learning And Autonomous Knowledge Generation'
authors: Zongyuan Li, Pengfei Li, Runnan Qi, Yanan Ni, Lumin Jiang, Hui Wu, Xuebo Zhang, Kuihua Huang, Xian Guo
conference: "Arxiv"
year: 2025
bibkey: li2025retrieval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01073'}
tags: ['RAG', 'Security', 'Applications', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
The lack of domain-specific data in the pre-training of Large Language Models
(LLMs) severely limits LLM-based decision systems in specialized applications,
while post-training a model in the scenarios requires significant computational
resources. In this paper, we present Retrial-Augmented Learning (RAL), a
reward-free self-supervised learning framework for LLMs that operates without
model training. By developing Retrieval-Augmented Generation (RAG) into a
module for organizing intermediate data, we realized a three-stage autonomous
knowledge generation of proposing a hypothesis, validating the hypothesis, and
generating the knowledge. The method is evaluated in the LLM-PySC2 environment,
a representative decision-making platform that combines sufficient complexity
with domain-specific knowledge requirements. Experiments demonstrate that the
proposed method effectively reduces hallucination by generating and utilizing
validated knowledge, and increases decision-making performance at an extremely
low cost. Meanwhile, the approach exhibits potential in
out-of-distribution(OOD) tasks, robustness, and transferability, making it a
cost-friendly but effective solution for decision-making problems and
autonomous knowledge generation.
