---
layout: publication
title: 'LLM Censorship: A Machine Learning Challenge Or A Computer Security Problem?'
authors: David Glukhov, Ilia Shumailov, Yarin Gal, Nicolas Papernot, Vardan Papyan
conference: "Arxiv"
year: 2023
bibkey: glukhov2023llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.10719'}
tags: ['Fine-Tuning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have exhibited impressive capabilities in
comprehending complex instructions. However, their blind adherence to provided
instructions has led to concerns regarding risks of malicious use. Existing
defence mechanisms, such as model fine-tuning or output censorship using LLMs,
have proven to be fallible, as LLMs can still generate problematic responses.
Commonly employed censorship approaches treat the issue as a machine learning
problem and rely on another LM to detect undesirable content in LLM outputs. In
this paper, we present the theoretical limitations of such semantic censorship
approaches. Specifically, we demonstrate that semantic censorship can be
perceived as an undecidable problem, highlighting the inherent challenges in
censorship that arise due to LLMs' programmatic and instruction-following
capabilities. Furthermore, we argue that the challenges extend beyond semantic
censorship, as knowledgeable attackers can reconstruct impermissible outputs
from a collection of permissible ones. As a result, we propose that the problem
of censorship needs to be reevaluated; it should be treated as a security
problem which warrants the adaptation of security-based approaches to mitigate
potential risks.
