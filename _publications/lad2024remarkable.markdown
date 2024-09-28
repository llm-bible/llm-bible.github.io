---
layout: publication
title: The Remarkable Robustness of LLMs Stages of Inference
authors: Lad Vedang, Gurnee Wes, Tegmark Max
conference: "Arxiv"
year: 2024
bibkey: lad2024remarkable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19384"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Security', 'Training Techniques']
---
We demonstrate and investigate the remarkable robustness of Large Language Models by deleting and swapping adjacent layers. We find that deleting and swapping interventions retain 72-95 of the original models prediction accuracy without fine-tuning whereas models with more layers exhibit more robustness. Based on the results of the layer-wise intervention and further experiments we hypothesize the existence of four universal stages of inference across eight different models detokenization feature engineering prediction ensembling and residual sharpening. The first stage integrates local information lifting raw token representations into higher-level contextual representations. Next is the iterative refinement of task and entity-specific features. Then the second half of the model begins with a phase transition where hidden representations align more with the vocabulary space due to specialized model components. Finally the last layer sharpens the following token distribution by eliminating obsolete features that add noise to the prediction.
