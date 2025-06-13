---
layout: publication
title: 'Factual Self-awareness In Language Models: Representation, Robustness, And Scaling'
authors: Hovhannes Tamoyan, Subhabrata Dutta, Iryna Gurevych
conference: "Arxiv"
year: 2025
bibkey: tamoyan2025factual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21399'}
tags: ['Interpretability and Explainability', 'Transformer', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Factual incorrectness in generated content is one of the primary concerns in ubiquitous deployment of large language models (LLMs). Prior findings suggest LLMs can (sometimes) detect factual incorrectness in their generated content (i.e., fact-checking post-generation). In this work, we provide evidence supporting the presence of LLMs' internal compass that dictate the correctness of factual recall at the time of generation. We demonstrate that for a given subject entity and a relation, LLMs internally encode linear features in the Transformer's residual stream that dictate whether it will be able to recall the correct attribute (that forms a valid entity-relation-attribute triplet). This self-awareness signal is robust to minor formatting variations. We investigate the effects of context perturbation via different example selection strategies. Scaling experiments across model sizes and training dynamics highlight that self-awareness emerges rapidly during training and peaks in intermediate layers. These findings uncover intrinsic self-monitoring capabilities within LLMs, contributing to their interpretability and reliability.
