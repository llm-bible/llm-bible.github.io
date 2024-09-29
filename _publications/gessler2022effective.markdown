---
layout: publication
title: "Microbert: Effective Training Of Low-resource Monolingual Berts Through Parameter Reduction And Multitask Learning"
authors: Gessler Luke, Zeldes Amir
conference: "Arxiv"
year: 2022
bibkey: gessler2022effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.12510"}
tags: ['BERT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Transformer language models (TLMs) are critical for most NLP tasks but they are difficult to create for low-resource languages because of how much pretraining data they require. In this work we investigate two techniques for training monolingual TLMs in a low-resource setting greatly reducing TLM size and complementing the masked language modeling objective with two linguistically rich supervised tasks (part-of-speech tagging and dependency parsing). Results from 7 diverse languages indicate that our model MicroBERT is able to produce marked improvements in downstream task evaluations relative to a typical monolingual TLM pretraining approach. Specifically we find that monolingual MicroBERT models achieve gains of up to 1837; for parser LAS and 1137; for NER F1 compared to a multilingual baseline mBERT while having less than 137; of its parameter count. We conclude reducing TLM parameter count and using labeled data for pretraining low-resource TLMs can yield large quality benefits and in some cases produce models that outperform multilingual approaches.
