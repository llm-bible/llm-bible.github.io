---
layout: publication
title: 'Neutralizing Bias In LLM Reasoning Using Entailment Graphs'
authors: Liang Cheng, Tianyi Li, Zhaowei Wang, Tianyang Liu, Mark Steedman
conference: "Arxiv"
year: 2025
bibkey: cheng2025neutralizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11614"}
tags: ['Security', 'Tools', 'Ethics and Bias', 'Reinforcement Learning']
---
LLMs are often claimed to be capable of Natural Language Inference (NLI),
which is widely regarded as a cornerstone of more complex forms of reasoning.
However, recent works show that LLMs still suffer from hallucinations in NLI
due to attestation bias, where LLMs overly rely on propositional memory to
build shortcuts. To solve the issue, we design an unsupervised framework to
construct counterfactual reasoning data and fine-tune LLMs to reduce
attestation bias. To measure bias reduction, we build bias-adversarial variants
of NLI datasets with randomly replaced predicates in premises while keeping
hypotheses unchanged. Extensive evaluations show that our framework can
significantly reduce hallucinations from attestation bias. Then, we further
evaluate LLMs fine-tuned with our framework on original NLI datasets and their
bias-neutralized versions, where original entities are replaced with randomly
sampled ones. Extensive results show that our framework consistently improves
inferential performance on both original and bias-neutralized NLI datasets.
