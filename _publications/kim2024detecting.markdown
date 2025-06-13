---
layout: publication
title: 'Detecting LLM Hallucination Through Layer-wise Information Deficiency: Analysis Of Unanswerable Questions And Ambiguous Prompts'
authors: Hazel Kim, Adel Bibi, Philip Torr, Yarin Gal
conference: "Arxiv"
year: 2024
bibkey: kim2024detecting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10246'}
tags: ['Prompting', 'Responsible AI', 'Training Techniques']
---
Large language models (LLMs) frequently generate confident yet inaccurate
responses, introducing significant risks for deployment in safety-critical
domains. We present a novel approach to detecting model hallucination through
systematic analysis of information flow across model layers when processing
inputs with insufficient or ambiguous context. Our investigation reveals that
hallucination manifests as usable information deficiencies in inter-layer
transmissions. While existing approaches primarily focus on final-layer output
analysis, we demonstrate that tracking cross-layer information dynamics
(\\(\mathcal\{L\}\\)I) provides robust indicators of model reliability, accounting
for both information gain and loss during computation. \\(\mathcal\{L\}\\)I improves
model reliability by immediately integrating with universal LLMs without
additional training or architectural modifications.
