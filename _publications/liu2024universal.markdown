---
layout: publication
title: 'On The Universal Truthfulness Hyperplane Inside Llms'
authors: Junteng Liu, Shiqi Chen, Yu Cheng, Junxian He
conference: "Arxiv"
year: 2024
bibkey: liu2024universal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.08582'}
tags: ['Reinforcement Learning', 'Training Techniques']
---
While large language models (LLMs) have demonstrated remarkable abilities
across various fields, hallucination remains a significant challenge. Recent
studies have explored hallucinations through the lens of internal
representations, proposing mechanisms to decipher LLMs' adherence to facts.
However, these approaches often fail to generalize to out-of-distribution data,
leading to concerns about whether internal representation patterns reflect
fundamental factual awareness, or only overfit spurious correlations on the
specific datasets. In this work, we investigate whether a universal
truthfulness hyperplane that distinguishes the model's factually correct and
incorrect outputs exists within the model. To this end, we scale up the number
of training datasets and conduct an extensive evaluation -- we train the
truthfulness hyperplane on a diverse collection of over 40 datasets and examine
its cross-task, cross-domain, and in-domain generalization. Our results
indicate that increasing the diversity of the training datasets significantly
enhances the performance in all scenarios, while the volume of data samples
plays a less critical role. This finding supports the optimistic hypothesis
that a universal truthfulness hyperplane may indeed exist within the model,
offering promising directions for future research.
