---
layout: publication
title: Explaining Sequence-level Knowledge Distillation As Data-augmentation For Neural
  Machine Translation
authors: Mitchell A. Gordon, Kevin Duh
conference: Arxiv
year: 2019
citations: 22
bibkey: gordon2019explaining
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.03334'}]
tags: [Efficiency and Optimization, Distillation]
---
Sequence-level knowledge distillation (SLKD) is a model compression technique
that leverages large, accurate teacher models to train smaller,
under-parameterized student models. Why does pre-processing MT data with SLKD
help us train smaller models? We test the common hypothesis that SLKD addresses
a capacity deficiency in students by "simplifying" noisy data points and find
it unlikely in our case. Models trained on concatenations of original and
"simplified" datasets generalize just as well as baseline SLKD. We then propose
an alternative hypothesis under the lens of data augmentation and
regularization. We try various augmentation strategies and observe that dropout
regularization can become unnecessary. Our methods achieve BLEU gains of
0.7-1.2 on TED Talks.