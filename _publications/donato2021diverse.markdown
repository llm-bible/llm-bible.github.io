---
layout: publication
title: Diverse Pretrained Context Encodings Improve Document Translation
authors: Donato Domenic, Yu Lei, Dyer Chris
conference: "ACL"
year: 2021
bibkey: donato2021diverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.03717"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We propose a new architecture for adapting a sentence45;level sequence45;to45;sequence transformer by incorporating multiple pretrained document context signals and assess the impact on translation performance of (1) different pretraining approaches for generating these signals (2) the quantity of parallel data for which document context is available and (3) conditioning on source target or source and target contexts. Experiments on the NIST Chinese45;English and IWSLT and WMT English45;German tasks support four general conclusions that using pretrained context representations markedly improves sample efficiency that adequate parallel data resources are crucial for learning to use document context that jointly conditioning on multiple context representations outperforms any single representation and that source context is more valuable for translation performance than target side context. Our best multi45;context model consistently outperforms the best existing context45;aware transformers.
