---
layout: publication
title: Constructing Datasets For Multi-hop Reading Comprehension Across Documents
authors: Johannes Welbl, Pontus Stenetorp, Sebastian Riedel
conference: Transactions of the Association for Computational Linguistics (TACL) Vol
  6 (2018) pages 287-302
year: 2017
citations: 114
bibkey: welbl2017constructing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1710.06481'}]
tags: [RAG]
---
Most Reading Comprehension methods limit themselves to queries which can be
answered using a single sentence, paragraph, or document. Enabling models to
combine disjoint pieces of textual evidence would extend the scope of machine
comprehension methods, but currently there exist no resources to train and test
this capability. We propose a novel task to encourage the development of models
for text understanding across multiple documents and to investigate the limits
of existing methods. In our task, a model learns to seek and combine evidence -
effectively performing multi-hop (alias multi-step) inference. We devise a
methodology to produce datasets for this task, given a collection of
query-answer pairs and thematically linked documents. Two datasets from
different domains are induced, and we identify potential pitfalls and devise
circumvention strategies. We evaluate two previously proposed competitive
models and find that one can integrate information across documents. However,
both models struggle to select relevant information, as providing documents
guaranteed to be relevant greatly improves their performance. While the models
outperform several strong baselines, their best accuracy reaches 42.9% compared
to human performance at 74.0% - leaving ample room for improvement.