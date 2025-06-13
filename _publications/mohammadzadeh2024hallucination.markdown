---
layout: publication
title: 'Hallucination Detox: Sensitivity Dropout (send) For Large Language Model Training'
authors: Shahrad Mohammadzadeh, Juan David Guerra, Marco Bonizzato, Reihaneh Rabbany, Golnoosh Farnadi
conference: "Arxiv"
year: 2024
bibkey: mohammadzadeh2024hallucination
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15460'}
tags: ['Reinforcement Learning', 'Training Techniques']
---
As large language models (LLMs) are increasingly deployed across various
industries, concerns regarding their reliability, particularly due to
hallucinations - outputs that are factually inaccurate or irrelevant to user
input - have grown. Our research investigates the relationship between the
training process and the emergence of hallucinations to address a key gap in
existing research that focuses primarily on post hoc detection and mitigation
strategies. Using models from the Pythia suite (70M - 12B parameters) and
several hallucination detection metrics, we analyze hallucination trends
throughout training and explore LLM internal dynamics. We introduce Sensitivity
Dropout (SenD), a novel training protocol designed to mitigate hallucinations
by reducing variance during training. SenD achieves this by deterministically
dropping embedding indices with significant variability, referred to as
Sensitive Embedding Indices. In addition, we develop an unsupervised
hallucination detection metric, Efficient EigenScore (EES), which approximates
the traditional EigenScore at 2x speed. This efficient metric is integrated
into our protocol, allowing SenD to be both computationally scalable and
effective at reducing hallucinations. Our empirical evaluation demonstrates
that our approach improves LLM reliability at test time by up to 40% compared
to normal training while also providing an efficient method to improve factual
accuracy when adapting LLMs to Wikipedia, Medical, and LegalBench domains.
