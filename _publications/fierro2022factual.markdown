---
layout: publication
title: 'Factual Consistency Of Multilingual Pretrained Language Models'
authors: Constanza Fierro, Anders Søgaard
conference: "Findings of the Association for Computational Linguistics ACL 2022 pages 3046-3052 Dublin Ireland. Association for Computational Linguistics"
year: 2022
bibkey: fierro2022factual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2203.11552'}
tags: ['BERT', 'Applications', 'Model Architecture']
---
Pretrained language models can be queried for factual knowledge, with
potential applications in knowledge base acquisition and tasks that require
inference. However, for that, we need to know how reliable this knowledge is,
and recent work has shown that monolingual English language models lack
consistency when predicting factual knowledge, that is, they fill-in-the-blank
differently for paraphrases describing the same fact. In this paper, we extend
the analysis of consistency to a multilingual setting. We introduce a resource,
mParaRel, and investigate (i) whether multilingual language models such as
mBERT and XLM-R are more consistent than their monolingual counterparts; and
(ii) if such models are equally consistent across languages. We find that mBERT
is as inconsistent as English BERT in English paraphrases, but that both mBERT
and XLM-R exhibit a high degree of inconsistency in English and even more so
for all the other 45 languages.
