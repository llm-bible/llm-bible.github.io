---
layout: publication
title: 'Probing Language Models On Their Knowledge Source'
authors: Zineddine Tighidet, Andrea Mogini, Jiali Mei, Benjamin Piwowarski, Patrick Gallinari
conference: "Arxiv"
year: 2024
bibkey: tighidet2024probing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05817'}
tags: ['Reinforcement Learning', 'Prompting', 'Tools']
---
Large Language Models (LLMs) often encounter conflicts between their learned,
internal (parametric knowledge, PK) and external knowledge provided during
inference (contextual knowledge, CK). Understanding how LLMs models prioritize
one knowledge source over the other remains a challenge. In this paper, we
propose a novel probing framework to explore the mechanisms governing the
selection between PK and CK in LLMs. Using controlled prompts designed to
contradict the model's PK, we demonstrate that specific model activations are
indicative of the knowledge source employed. We evaluate this framework on
various LLMs of different sizes and demonstrate that mid-layer activations,
particularly those related to relations in the input, are crucial in predicting
knowledge source selection, paving the way for more reliable models capable of
handling knowledge conflicts effectively.
