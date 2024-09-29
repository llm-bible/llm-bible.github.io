---
layout: publication
title: TADA Efficient Task45;agnostic Domain Adaptation For Transformers
authors: Hung Chia-chien, Lange Lukas, Strötgen Jannik
conference: "Arxiv"
year: 2023
bibkey: hung2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12717"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Intermediate training of pre45;trained transformer45;based language models on domain45;specific data leads to substantial gains for downstream tasks. To increase efficiency and prevent catastrophic forgetting alleviated from full domain45;adaptive pre45;training approaches such as adapters have been developed. However these require additional parameters for each layer and are criticized for their limited expressiveness. In this work we introduce TADA a novel task45;agnostic domain adaptation method which is modular parameter45;efficient and thus data45;efficient. Within TADA we retrain the embeddings to learn domain45;aware input representations and tokenizers for the transformer encoder while freezing all other parameters of the model. Then task45;specific fine45;tuning is performed. We further conduct experiments with meta45;embeddings and newly introduced meta45;tokenizers resulting in one model per task in multi45;domain use cases. Our broad evaluation in 4 downstream tasks for 14 domains across single45; and multi45;domain setups and high45; and low45;resource scenarios reveals that TADA is an effective and efficient alternative to full domain45;adaptive pre45;training and adapters for domain adaptation while not introducing additional parameters or complex training steps.
