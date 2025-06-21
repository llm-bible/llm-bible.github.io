---
layout: publication
title: Are All Languages Created Equal In Multilingual BERT?
authors: Shijie Wu, Mark Dredze
conference: Arxiv
year: 2020
citations: 61
bibkey: wu2020are
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.09093'}]
tags: [BERT, Pre-Training, Language Modeling]
---
Multilingual BERT (mBERT) trained on 104 languages has shown surprisingly
good cross-lingual performance on several NLP tasks, even without explicit
cross-lingual signals. However, these evaluations have focused on cross-lingual
transfer with high-resource languages, covering only a third of the languages
covered by mBERT. We explore how mBERT performs on a much wider set of
languages, focusing on the quality of representation for low-resource
languages, measured by within-language performance. We consider three tasks:
Named Entity Recognition (99 languages), Part-of-speech Tagging, and Dependency
Parsing (54 languages each). mBERT does better than or comparable to baselines
on high resource languages but does much worse for low resource languages.
Furthermore, monolingual BERT models for these languages do even worse. Paired
with similar languages, the performance gap between monolingual BERT and mBERT
can be narrowed. We find that better models for low resource languages require
more efficient pretraining techniques or more data.