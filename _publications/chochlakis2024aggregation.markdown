---
layout: publication
title: 'Aggregation Artifacts In Subjective Tasks Collapse Large Language Models'' Posteriors'
authors: Georgios Chochlakis, Alexandros Potamianos, Kristina Lerman, Shrikanth Narayanan
conference: "Proceedings of the 2025 Conference of the North American Chapter of the Association for Computational Linguistics Human Language Technologies pages 5513-5528 Albuquerque New Mexico April 2025"
year: 2024
bibkey: chochlakis2024aggregation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13776"}
tags: ['Pre-Training', 'Ethics and Bias', 'Reinforcement Learning', 'Training Techniques', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
In-context Learning (ICL) has become the primary method for performing natural language tasks with Large Language Models (LLMs). The knowledge acquired during pre-training is crucial for this few-shot capability, providing the model with task priors. However, recent studies have shown that ICL predominantly relies on retrieving task priors rather than "learning" to perform tasks. This limitation is particularly evident in complex subjective domains such as emotion and morality, where priors significantly influence posterior predictions. In this work, we examine whether this is the result of the aggregation used in corresponding datasets, where trying to combine low-agreement, disparate annotations might lead to annotation artifacts that create detrimental noise in the prompt. Moreover, we evaluate the posterior bias towards certain annotators by grounding our study in appropriate, quantitative measures of LLM priors. Our results indicate that aggregation is a confounding factor in the modeling of subjective tasks, and advocate focusing on modeling individuals instead. However, aggregation does not explain the entire gap between ICL and the state of the art, meaning other factors in such tasks also account for the observed phenomena. Finally, by rigorously studying annotator-level labels, we find that it is possible for minority annotators to both better align with LLMs and have their perspectives further amplified.
