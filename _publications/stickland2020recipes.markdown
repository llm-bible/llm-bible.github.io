---
layout: publication
title: 'Recipes For Adapting Pre-trained Monolingual And Multilingual Models To Machine Translation'
authors: Asa Cooper Stickland, Xian Li, Marjan Ghazvininejad
conference: "Arxiv"
year: 2020
bibkey: stickland2020recipes
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.14911"}
tags: ['Fine-Tuning', 'Pre-Training', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
There has been recent success in pre-training on monolingual data and
fine-tuning on Machine Translation (MT), but it remains unclear how to best
leverage a pre-trained model for a given MT task. This paper investigates the
benefits and drawbacks of freezing parameters, and adding new ones, when
fine-tuning a pre-trained model on MT. We focus on 1) Fine-tuning a model
trained only on English monolingual data, BART. 2) Fine-tuning a model trained
on monolingual data from 25 languages, mBART. For BART we get the best
performance by freezing most of the model parameters, and adding extra
positional embeddings. For mBART we match or outperform the performance of
naive fine-tuning for most language pairs with the encoder, and most of the
decoder, frozen. The encoder-decoder attention parameters are most important to
fine-tune. When constraining ourselves to an out-of-domain training set for
Vietnamese to English we see the largest improvements over the fine-tuning
baseline.
