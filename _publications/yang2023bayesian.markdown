---
layout: publication
title: 'Bayesian Low-rank Adaptation For Large Language Models'
authors: Adam X. Yang, Maxime Robeyns, Xi Wang, Laurence Aitchison
conference: "Arxiv"
year: 2023
bibkey: yang2023bayesian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.13111"}
tags: ['Fine-Tuning', 'Training Techniques', 'Tools', 'Pretraining Methods']
---
Low-rank adaptation (LoRA) has emerged as a new paradigm for cost-efficient
fine-tuning of large language models (LLMs). However, fine-tuned LLMs often
become overconfident especially when fine-tuned on small datasets. Bayesian
methods, with their inherent ability to estimate uncertainty, serve as potent
tools to mitigate overconfidence and enhance calibration. In this work, we
introduce Laplace-LoRA, which applies a Bayesian approach to the LoRA
parameters. Specifically, Laplace-LoRA applies a Laplace approximation to the
posterior over the LoRA parameters, considerably improving the calibration of
fine-tuned LLMs.
