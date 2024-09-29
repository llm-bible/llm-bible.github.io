---
layout: publication
title: The Remarkable Robustness Of Llms Stages Of Inference
authors: Lad Vedang, Gurnee Wes, Tegmark Max
conference: "Arxiv"
year: 2024
bibkey: lad2024remarkable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19384"}
tags: ['Pretraining Methods', 'Security', 'Tokenization']
---
We demonstrate and investigate the remarkable robustness of Large Language Models by deleting and swapping adjacent layers. We find that deleting and swapping interventions retain 7245;9537; of the original models prediction accuracy without fine45;tuning whereas models with more layers exhibit more robustness. Based on the results of the layer45;wise intervention and further experiments we hypothesize the existence of four universal stages of inference across eight different models detokenization feature engineering prediction ensembling and residual sharpening. The first stage integrates local information lifting raw token representations into higher45;level contextual representations. Next is the iterative refinement of task and entity45;specific features. Then the second half of the model begins with a phase transition where hidden representations align more with the vocabulary space due to specialized model components. Finally the last layer sharpens the following token distribution by eliminating obsolete features that add noise to the prediction.
