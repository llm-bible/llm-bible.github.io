---
layout: publication
title: Emergent Properties Of Finetuned Language Representation Models
authors: Matton Alexandre, De Oliveira Luke
conference: "Arxiv"
year: 2019
bibkey: matton2019emergent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.10832"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large self45;supervised transformer45;based language representation models have recently received significant amounts of attention and have produced state45;of45;the45;art results across a variety of tasks simply by scaling up pre45;training on larger and larger corpora. Such models usually produce high dimensional vectors on top of which additional task45;specific layers and architectural modifications are added to adapt them to specific downstream tasks. Though there exists ample evidence that such models work well we aim to understand what happens when they work well. We analyze the redundancy and location of information contained in output vectors for one such language representation model 45;45; BERT. We show empirical evidence that the CLS embedding in BERT contains highly redundant information and can be compressed with minimal loss of accuracy especially for finetuned models dovetailing into open threads in the field about the role of over45;parameterization in learning. We also shed light on the existence of specific output dimensions which alone give very competitive results when compared to using all dimensions of output vectors.
