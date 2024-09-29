---
layout: publication
title: "Spactor-t5: Pre-training T5 Models With Span Corruption And Replaced Token Detection"
authors: Ye Ke, Jiang Heinrich, Rostamizadeh Afshin, Chakrabarti Ayan, Desalvo Giulia, Kagy Jean-françois, Karydas Lazaros, Citovsky Gui, Kumar Sanjiv
conference: "Arxiv"
year: 2024
bibkey: ye2024spactor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13160"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Pre-training large language models is known to be extremely resource intensive and often times inefficient under-utilizing the information encapsulated in the training text sequences. In this paper we present SpacTor a new training procedure consisting of (1) a hybrid objective combining span corruption (SC) and token replacement detection (RTD) and (2) a two-stage curriculum that optimizes the hybrid objective over the initial (tau) iterations then transitions to standard SC loss. We show empirically that the effectiveness of the hybrid objective is tied to the two-stage pre-training schedule and provide extensive analysis on why this is the case. In our experiments with encoder-decoder architectures (T5) on a variety of NLP tasks SpacTor-T5 yields the same downstream performance as standard SC pre-training while enabling a 5037; reduction in pre-training iterations and 4037; reduction in total FLOPs. Alternatively given the same amount of computing budget we find that SpacTor results in significantly improved downstream benchmark performance.
