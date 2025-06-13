---
layout: publication
title: 'It''s Not Greek To Mbert: Inducing Word-level Translations From Multilingual BERT'
authors: Hila Gonen, Shauli Ravfogel, Yanai Elazar, Yoav Goldberg
conference: "Arxiv"
year: 2020
bibkey: gonen2020not
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2010.08275'}
tags: ['Training Techniques', 'BERT', 'Tools', 'Fine-Tuning', 'Model Architecture', 'Pretraining Methods']
---
Recent works have demonstrated that multilingual BERT (mBERT) learns rich
cross-lingual representations, that allow for transfer across languages. We
study the word-level translation information embedded in mBERT and present two
simple methods that expose remarkable translation capabilities with no
fine-tuning. The results suggest that most of this information is encoded in a
non-linear way, while some of it can also be recovered with purely linear
tools. As part of our analysis, we test the hypothesis that mBERT learns
representations which contain both a language-encoding component and an
abstract, cross-lingual component, and explicitly identify an empirical
language-identity subspace within mBERT representations.
