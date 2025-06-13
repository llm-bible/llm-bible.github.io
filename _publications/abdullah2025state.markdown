---
layout: publication
title: 'State-of-the-art Translation Of Text-to-gloss Using Mbart : A Case Study Of Bangla'
authors: Sharif Md. Abdullah, Abhijit Paul, Shebuti Rayana, Ahmedul Kabir, Zarif Masud
conference: "Arxiv"
year: 2025
bibkey: abdullah2025state
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.02293'}
tags: ['Attention Mechanism', 'Language Modeling', 'RAG', 'Training Techniques', 'Model Architecture', 'BERT', 'Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Despite a large deaf and dumb population of 1.7 million, Bangla Sign Language
(BdSL) remains a understudied domain. Specifically, there are no works on
Bangla text-to-gloss translation task. To address this gap, we begin by
addressing the dataset problem. We take inspiration from grammatical rule based
gloss generation used in Germany and American sign langauage (ASL) and adapt it
for BdSL. We also leverage LLM to generate synthetic data and use
back-translation, text generation for data augmentation. With dataset prepared,
we started experimentation. We fine-tuned pretrained mBART-50 and
mBERT-multiclass-uncased model on our dataset. We also trained GRU, RNN and a
novel seq-to-seq model with multi-head attention. We observe significant high
performance (ScareBLEU=79.53) with fine-tuning pretrained mBART-50 multilingual
model from Facebook. We then explored why we observe such high performance with
mBART. We soon notice an interesting property of mBART -- it was trained on
shuffled and masked text data. And as we know, gloss form has shuffling
property. So we hypothesize that mBART is inherently good at text-to-gloss
tasks. To find support against this hypothesis, we trained mBART-50 on
PHOENIX-14T benchmark and evaluated it with existing literature. Our mBART-50
finetune demonstrated State-of-the-Art performance on PHOENIX-14T benchmark,
far outperforming existing models in all 6 metrics (ScareBLEU = 63.89, BLEU-1 =
55.14, BLEU-2 = 38.07, BLEU-3 = 27.13, BLEU-4 = 20.68, COMET = 0.624). Based on
the results, this study proposes a new paradigm for text-to-gloss task using
mBART models. Additionally, our results show that BdSL text-to-gloss task can
greatly benefit from rule-based synthetic dataset.
