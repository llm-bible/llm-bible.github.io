---
layout: publication
title: Efficient Domain Adaptation Of Language Models Via Adaptive Tokenization
authors: Sachidananda Vin, Kessler Jason S., Lai Yi-an
conference: "Arxiv"
year: 2021
bibkey: sachidananda2021efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.07460"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Tokenization', 'Training Techniques']
---
Contextual embedding45;based language models trained on large data sets such as BERT and RoBERTa provide strong performance across a wide range of tasks and are ubiquitous in modern NLP. It has been observed that fine45;tuning these models on tasks involving data from domains different from that on which they were pretrained can lead to suboptimal performance. Recent work has explored approaches to adapt pretrained language models to new domains by incorporating additional pretraining using domain45;specific corpora and task data. We propose an alternative approach for transferring pretrained language models to new domains by adapting their tokenizers. We show that domain45;specific subword sequences can be efficiently determined directly from divergences in the conditional token distributions of the base and domain45;specific corpora. In datasets from four disparate domains we find adaptive tokenization on a pretrained RoBERTa model provides 9737; of the performance benefits of domain specific pretraining. Our approach produces smaller models and less training and inference time than other approaches using tokenizer augmentation. While adaptive tokenization incurs a 637; increase in model parameters in our experimentation due to the introduction of 10k new domain45;specific tokens our approach using 64 vCPUs is 72x faster than further pretraining the language model on domain45;specific corpora on 8 TPUs.
