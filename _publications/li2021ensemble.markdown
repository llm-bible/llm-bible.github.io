---
layout: publication
title: Ensemble ALBERT On Squad 2.0
authors: Li Shilun, Li Renee, Peng Veronica
conference: "Arxiv"
year: 2021
bibkey: li2021ensemble
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.09665"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Machine question answering is an essential yet challenging task in natural language processing. Recently Pre45;trained Contextual Embeddings (PCE) models like Bidirectional Encoder Representations from Transformers (BERT) and A Lite BERT (ALBERT) have attracted lots of attention due to their great performance in a wide range of NLP tasks. In our Paper we utilized the fine45;tuned ALBERT models and implemented combinations of additional layers (e.g. attention layer RNN layer) on top of them to improve model performance on Stanford Question Answering Dataset (SQuAD 2.0). We implemented four different models with different layers on top of ALBERT45;base model and two other models based on ALBERT45;xlarge and ALBERT45;xxlarge. We compared their performance to our baseline model ALBERT45;base45;v2 + ALBERT45;SQuAD45;out with details. Our best45;performing individual model is ALBERT45;xxlarge + ALBERT45;SQuAD45;out which achieved an F1 score of 88.435 on the dev set. Furthermore we have implemented three different ensemble algorithms to boost overall performance. By passing in several best45;performing models results into our weighted voting ensemble algorithm our final result ranks first on the Stanford CS224N Test PCE SQuAD Leaderboard with F1 = 90.123.
