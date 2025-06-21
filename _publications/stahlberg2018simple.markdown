---
layout: publication
title: 'Simple Fusion: Return Of The Language Model'
authors: Felix Stahlberg, James Cross, Veselin Stoyanov
conference: Arxiv
year: 2018
citations: 19
bibkey: stahlberg2018simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.00125'}]
tags: [RAG, Training Techniques, Model Architecture]
---
Neural Machine Translation (NMT) typically leverages monolingual data in
training through backtranslation. We investigate an alternative simple method
to use monolingual data for NMT training: We combine the scores of a
pre-trained and fixed language model (LM) with the scores of a translation
model (TM) while the TM is trained from scratch. To achieve that, we train the
translation model to predict the residual probability of the training data
added to the prediction of the LM. This enables the TM to focus its capacity on
modeling the source sentence since it can rely on the LM for fluency. We show
that our method outperforms previous approaches to integrate LMs into NMT while
the architecture is simpler as it does not require gating networks to balance
TM and LM. We observe gains of between +0.24 and +2.36 BLEU on all four test
sets (English-Turkish, Turkish-English, Estonian-English, Xhosa-English) on top
of ensembles without LM. We compare our method with alternative ways to utilize
monolingual data such as backtranslation, shallow fusion, and cold fusion.