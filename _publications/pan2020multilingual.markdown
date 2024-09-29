---
layout: publication
title: Multilingual BERT Post-Pretraining Alignment
authors: Pan Lin, Hang Chung-wei, Qi Haode, Shah Abhishek, Potdar Saloni, Yu Mo
conference: "Arxiv"
year: 2020
bibkey: pan2020multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.12547"}
tags: ['BERT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We propose a simple method to align multilingual contextual embeddings as a post-pretraining step for improved zero-shot cross-lingual transferability of the pretrained models. Using parallel data our method aligns embeddings on the word level through the recently proposed Translation Language Modeling objective as well as on the sentence level via contrastive learning and random input shuffling. We also perform sentence-level code-switching with English when finetuning on downstream tasks. On XNLI our best model (initialized from mBERT) improves over mBERT by 4.7 in the zero-shot setting and achieves comparable result to XLM for translate-train while using less than 18 of the same parallel data and 31 less model parameters. On MLQA our model outperforms XLM-R_Base that has 57 more parameters than ours.
