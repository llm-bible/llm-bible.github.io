---
layout: publication
title: 'On The Diversity Of Synthetic Data And Its Impact On Training Large Language Models'
authors: Hao Chen, Abdul Waheed, Xiang Li, Yidong Wang, Jindong Wang, Bhiksha Raj, Marah I. Abdin
conference: "Arxiv"
year: 2024
bibkey: chen2024diversity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15226"}
tags: ['Fine-Tuning', 'Pre-Training', 'Agentic', 'Training Techniques', 'Pretraining Methods']
---
The rise of Large Language Models (LLMs) has accentuated the need for
diverse, high-quality pre-training data. Synthetic data emerges as a viable
solution to the challenges of data scarcity and inaccessibility. While previous
literature has focused predominantly on the quality and quantity of real data,
our work enables the measurement of diversity in synthetic data and explores
its impact on LLM performance. We study the downstream effects of synthetic
data diversity during both the pre-training and fine-tuning stages by
introducing a new diversity metric, \textit\{LLM cluster-agent\}, designed to
evaluate the diversity of synthetic datasets. Through a series of controlled
experiments with models of 350M and 1.4B parameters, we demonstrate that the
proposed cluster-based LLM scoring of diversity correlates positively with both
pre-training and supervised fine-tuning performance. Our findings also reveal
that synthetic data diversity in pre-training affects supervised fine-tuning
more significantly than pre-training itself, even for smaller models. We hope
this study advances our understanding of the optimal use of synthetic data in
LLM training and opens new avenues for efficient data generation processes.
