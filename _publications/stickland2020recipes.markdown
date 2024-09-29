---
layout: publication
title: Recipes For Adapting Pre45;trained Monolingual And Multilingual Models To Machine Translation
authors: Stickland Asa Cooper, Li Xian, Ghazvininejad Marjan
conference: "Arxiv"
year: 2020
bibkey: stickland2020recipes
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.14911"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Training Techniques']
---
There has been recent success in pre45;training on monolingual data and fine45;tuning on Machine Translation (MT) but it remains unclear how to best leverage a pre45;trained model for a given MT task. This paper investigates the benefits and drawbacks of freezing parameters and adding new ones when fine45;tuning a pre45;trained model on MT. We focus on 1) Fine45;tuning a model trained only on English monolingual data BART. 2) Fine45;tuning a model trained on monolingual data from 25 languages mBART. For BART we get the best performance by freezing most of the model parameters and adding extra positional embeddings. For mBART we match or outperform the performance of naive fine45;tuning for most language pairs with the encoder and most of the decoder frozen. The encoder45;decoder attention parameters are most important to fine45;tune. When constraining ourselves to an out45;of45;domain training set for Vietnamese to English we see the largest improvements over the fine45;tuning baseline.
