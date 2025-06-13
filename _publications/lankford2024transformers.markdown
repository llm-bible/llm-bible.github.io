---
layout: publication
title: 'Transformers For Low-resource Languages: Is F\''eidir Linn!'
authors: Séamus Lankford, Haithem Afli, Andy Way
conference: "Proceedings of Machine Translation Summit XVIII Research Track 2021"
year: 2024
bibkey: lankford2024transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01985"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
The Transformer model is the state-of-the-art in Machine Translation.
However, in general, neural translation models often under perform on language
pairs with insufficient training data. As a consequence, relatively few
experiments have been carried out using this architecture on low-resource
language pairs. In this study, hyperparameter optimization of Transformer
models in translating the low-resource English-Irish language pair is
evaluated. We demonstrate that choosing appropriate parameters leads to
considerable performance improvements. Most importantly, the correct choice of
subword model is shown to be the biggest driver of translation performance.
SentencePiece models using both unigram and BPE approaches were appraised.
Variations on model architectures included modifying the number of layers,
testing various regularisation techniques and evaluating the optimal number of
heads for attention. A generic 55k DGT corpus and an in-domain 88k public admin
corpus were used for evaluation. A Transformer optimized model demonstrated a
BLEU score improvement of 7.8 points when compared with a baseline RNN model.
Improvements were observed across a range of metrics, including TER, indicating
a substantially reduced post editing effort for Transformer optimized models
with 16k BPE subword models. Bench-marked against Google Translate, our
translation engines demonstrated significant improvements. The question of
whether or not Transformers can be used effectively in a low-resource setting
of English-Irish translation has been addressed. Is f\'eidir linn - yes we can.
