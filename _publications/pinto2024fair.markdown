---
layout: publication
title: 'The Fair Language Model Paradox'
authors: Andrea Pinto, Tomer Galanti, Randall Balestriero
conference: "Arxiv"
year: 2024
bibkey: pinto2024fair
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11985"}
tags: ['Applications', 'Ethics and Bias', 'Bias Mitigation', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Fairness']
---
Large Language Models (LLMs) are widely deployed in real-world applications,
yet little is known about their training dynamics at the token level.
Evaluation typically relies on aggregated training loss, measured at the batch
level, which overlooks subtle per-token biases arising from (i) varying
token-level dynamics and (ii) structural biases introduced by hyperparameters.
While weight decay is commonly used to stabilize training, we reveal that it
silently introduces performance biases detectable only at the token level. In
fact, we empirically show across different dataset sizes, model architectures
and sizes ranging from 270M to 3B parameters that as weight decay increases,
low-frequency tokens are disproportionately depreciated. This is particularly
concerning, as these neglected low-frequency tokens represent the vast majority
of the token distribution in most languages, calling for novel regularization
techniques that ensure fairness across all available tokens.
