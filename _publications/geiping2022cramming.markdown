---
layout: publication
title: Cramming Training A Language Model On A Single GPU In One Day
authors: Geiping Jonas, Goldstein Tom
conference: "Arxiv"
year: 2022
bibkey: geiping2022cramming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.14034"}
tags: ['BERT', 'Efficiency And Optimization', 'Language Modeling', 'Large Scale Training', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques', 'Transformer']
---
Recent trends in language modeling have focused on increasing performance through scaling and have resulted in an environment where training language models is out of reach for most researchers and practitioners. While most in the community are asking how to push the limits of extreme computation we ask the opposite question How far can we get with a single GPU in just one day We investigate the downstream performance achievable with a transformer-based language model trained completely from scratch with masked language modeling for a single day on a single consumer GPU. Aside from re-analyzing nearly all components of the pretraining pipeline for this scenario and providing a modified pipeline with performance close to BERT we investigate why scaling down is hard and which modifications actually improve performance in this scenario. We provide evidence that even in this constrained setting performance closely follows scaling laws observed in large-compute settings. Through the lens of scaling laws we categorize a range of recent improvements to training and architecture and discuss their merit and practical applicability (or lack thereof) for the limited compute setting.
