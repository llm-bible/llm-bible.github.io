---
layout: publication
title: A Neural Interlingua For Multilingual Machine Translation
authors: Yichao Lu et al.
conference: Arxiv
year: 2018
citations: 18
bibkey: lu2018neural
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.08198'}]
tags: [Reinforcement Learning, Survey Paper]
---
We incorporate an explicit neural interlingua into a multilingual
encoder-decoder neural machine translation (NMT) architecture. We demonstrate
that our model learns a language-independent representation by performing
direct zero-shot translation (without using pivot translation), and by using
the source sentence embeddings to create an English Yelp review classifier
that, through the mediation of the neural interlingua, can also classify French
and German reviews. Furthermore, we show that, despite using a smaller number
of parameters than a pairwise collection of bilingual NMT models, our approach
produces comparable BLEU scores for each language pair in WMT15.