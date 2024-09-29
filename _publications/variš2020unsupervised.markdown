---
layout: publication
title: Unsupervised Pretraining For Neural Machine Translation Using Elastic Weight Consolidation
authors: Variš Dušan, Bojar Ondřej
conference: "Arxiv"
year: 2020
bibkey: variš2020unsupervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.09403"}
tags: ['Applications', 'Language Modeling', 'Pretraining Methods', 'Training Techniques']
---
This work presents our ongoing research of unsupervised pretraining in neural machine translation (NMT). In our method we initialize the weights of the encoder and decoder with two language models that are trained with monolingual data and then fine45;tune the model on parallel data using Elastic Weight Consolidation (EWC) to avoid forgetting of the original language modeling tasks. We compare the regularization by EWC with the previous work that focuses on regularization by language modeling objectives. The positive result is that using EWC with the decoder achieves BLEU scores similar to the previous work. However the model converges 245;3 times faster and does not require the original unlabeled training data during the fine45;tuning stage. In contrast the regularization using EWC is less effective if the original and new tasks are not closely related. We show that initializing the bidirectional NMT encoder with a left45;to45;right language model and forcing the model to remember the original left45;to45;right language modeling task limits the learning capacity of the encoder for the whole bidirectional context.
