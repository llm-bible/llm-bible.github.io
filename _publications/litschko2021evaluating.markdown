---
layout: publication
title: 'Evaluating Multilingual Text Encoders For Unsupervised Cross-lingual Retrieval'
authors: Robert Litschko, Ivan Vulić, Simone Paolo Ponzetto, Goran Glavaš
conference: "Arxiv"
year: 2021
bibkey: litschko2021evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2101.08370'}
tags: ['Transformer', 'Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Pretrained multilingual text encoders based on neural Transformer
architectures, such as multilingual BERT (mBERT) and XLM, have achieved strong
performance on a myriad of language understanding tasks. Consequently, they
have been adopted as a go-to paradigm for multilingual and cross-lingual
representation learning and transfer, rendering cross-lingual word embeddings
(CLWEs) effectively obsolete. However, questions remain to which extent this
finding generalizes 1) to unsupervised settings and 2) for ad-hoc cross-lingual
IR (CLIR) tasks. Therefore, in this work we present a systematic empirical
study focused on the suitability of the state-of-the-art multilingual encoders
for cross-lingual document and sentence retrieval tasks across a large number
of language pairs. In contrast to supervised language understanding, our
results indicate that for unsupervised document-level CLIR -- a setup with no
relevance judgments for IR-specific fine-tuning -- pretrained encoders fail to
significantly outperform models based on CLWEs. For sentence-level CLIR, we
demonstrate that state-of-the-art performance can be achieved. However, the
peak performance is not met using the general-purpose multilingual text
encoders `off-the-shelf', but rather relying on their variants that have been
further specialized for sentence understanding tasks.
