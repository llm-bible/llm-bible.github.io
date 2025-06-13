---
layout: publication
title: 'Certifying Counterfactual Bias In Llms'
authors: Isha Chaudhary, Qian Hu, Manoj Kumar, Morteza Ziyadi, Rahul Gupta, Gagandeep Singh
conference: "Arxiv"
year: 2024
bibkey: chaudhary2024certifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.18780'}
tags: ['Ethics and Bias', 'Prompting', 'Tools']
---
Large Language Models (LLMs) can produce biased responses that can cause
representational harms. However, conventional studies are insufficient to
thoroughly evaluate biases across LLM responses for different demographic
groups (a.k.a. counterfactual bias), as they do not scale to large number of
inputs and do not provide guarantees. Therefore, we propose the first
framework, LLMCert-B that certifies LLMs for counterfactual bias on
distributions of prompts. A certificate consists of high-confidence bounds on
the probability of unbiased LLM responses for any set of counterfactual prompts
- prompts differing by demographic groups, sampled from a distribution. We
illustrate counterfactual bias certification for distributions of
counterfactual prompts created by applying prefixes sampled from prefix
distributions, to a given set of prompts. We consider prefix distributions
consisting random token sequences, mixtures of manual jailbreaks, and
perturbations of jailbreaks in LLM's embedding space. We generate non-trivial
certificates for SOTA LLMs, exposing their vulnerabilities over distributions
of prompts generated from computationally inexpensive prefix distributions.
