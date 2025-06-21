---
layout: publication
title: Correction Of Automatic Speech Recognition With Transformer Sequence-to-sequence
  Model
authors: Oleksii Hrinchuk, Mariya Popova, Boris Ginsburg
conference: Arxiv
year: 2019
citations: 42
bibkey: hrinchuk2019correction
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.10697'}]
tags: [Transformer, Applications]
---
In this work, we introduce a simple yet efficient post-processing model for
automatic speech recognition (ASR). Our model has Transformer-based
encoder-decoder architecture which "translates" ASR model output into
grammatically and semantically correct text. We investigate different
strategies for regularizing and optimizing the model and show that extensive
data augmentation and the initialization with pre-trained weights are required
to achieve good performance. On the LibriSpeech benchmark, our method
demonstrates significant improvement in word error rate over the baseline
acoustic model with greedy decoding, especially on much noisier dev-other and
test-other portions of the evaluation dataset. Our model also outperforms
baseline with 6-gram language model re-scoring and approaches the performance
of re-scoring with Transformer-XL neural language model.