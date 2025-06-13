---
layout: publication
title: 'Detecting Memorization In Large Language Models'
authors: Eduardo Slonski
conference: "Arxiv"
year: 2024
bibkey: slonski2024detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01014"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Interpretability', 'Interpretability and Explainability']
---
Large language models (LLMs) have achieved impressive results in natural
language processing but are prone to memorizing portions of their training
data, which can compromise evaluation metrics, raise privacy concerns, and
limit generalization. Traditional methods for detecting memorization rely on
output probabilities or loss functions, often lacking precision due to
confounding factors like common language patterns. In this paper, we introduce
an analytical method that precisely detects memorization by examining neuron
activations within the LLM. By identifying specific activation patterns that
differentiate between memorized and not memorized tokens, we train
classification probes that achieve near-perfect accuracy. The approach can also
be applied to other mechanisms, such as repetition, as demonstrated in this
study, highlighting its versatility. Intervening on these activations allows us
to suppress memorization without degrading overall performance, enhancing
evaluation integrity by ensuring metrics reflect genuine generalization.
Additionally, our method supports large-scale labeling of tokens and sequences,
crucial for next-generation AI models, improving training efficiency and
results. Our findings contribute to model interpretability and offer practical
tools for analyzing and controlling internal mechanisms in LLMs.
