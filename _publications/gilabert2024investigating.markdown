---
layout: publication
title: 'Investigating The Translation Capabilities Of Large Language Models Trained On Parallel Data Only'
authors: Javier García Gilabert, Carlos Escolano, Aleix Sant Savall, Francesca De Luca Fornaciari, Audrey Mash, Xixian Liao, Maite Melero
conference: "Arxiv"
year: 2024
bibkey: gilabert2024investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.09140'}
tags: ['Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'Pretraining Methods']
---
In recent years, Large Language Models (LLMs) have demonstrated exceptional
proficiency across a broad spectrum of Natural Language Processing (NLP) tasks,
including Machine Translation. However, previous methods predominantly relied
on iterative processes such as instruction fine-tuning or continual
pre-training, leaving unexplored the challenges of training LLMs solely on
parallel data. In this work, we introduce PLUME (Parallel Language Model), a
collection of three 2B LLMs featuring varying vocabulary sizes (32k, 128k, and
256k) trained exclusively on Catalan-centric parallel examples. These models
perform comparably to previous encoder-decoder architectures on 16 supervised
translation directions and 56 zero-shot ones. Utilizing this set of models, we
conduct a thorough investigation into the translation capabilities of LLMs,
probing their performance, the impact of the different elements of the prompt,
and their cross-lingual representation space.
