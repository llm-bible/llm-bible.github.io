---
layout: publication
title: 'Drop Dropout On Single-epoch Language Model Pretraining'
authors: Houjun Liu, John Bauer, Christopher D. Manning
conference: "Arxiv"
year: 2025
bibkey: liu2025drop
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24788"}
tags: ['GPT', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Originally, dropout was seen as a breakthrough regularization technique that reduced overfitting and improved performance in almost all applications of deep learning by reducing overfitting. Yet, single-epoch pretraining tasks common to modern LLMs yield minimal overfitting, leading to dropout not being used for large LLMs. Nevertheless, no thorough empirical investigation has been done on the role of dropout in LM pretraining. Through experiments in single-epoch pretraining of both masked (BERT) and autoregressive (Pythia 160M and 1.4B) LMs with varying levels of dropout, we find that downstream performance in language modeling, morpho-syntax (BLiMP), question answering (SQuAD), and natural-language inference (MNLI) improves when dropout is not applied during pretraining. We additionally find that the recently-introduced "early dropout" also degrades performance over applying no dropout at all. We further investigate the models' editability, and find that models trained without dropout are more successful in gradient-based model editing (MEND) and equivalent in representation-based model editing (ReFT). Therefore, we advocate to drop dropout during single-epoch pretraining.
