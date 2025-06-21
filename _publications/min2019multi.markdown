---
layout: publication
title: Multi-hop Reading Comprehension Through Question Decomposition And Rescoring
authors: Sewon Min, Victor Zhong, Luke Zettlemoyer, Hannaneh Hajishirzi
conference: Arxiv
year: 2019
citations: 60
bibkey: min2019multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.02916'}]
tags: [RAG]
---
Multi-hop Reading Comprehension (RC) requires reasoning and aggregation
across several paragraphs. We propose a system for multi-hop RC that decomposes
a compositional question into simpler sub-questions that can be answered by
off-the-shelf single-hop RC models. Since annotations for such decomposition
are expensive, we recast sub-question generation as a span prediction problem
and show that our method, trained using only 400 labeled examples, generates
sub-questions that are as effective as human-authored sub-questions. We also
introduce a new global rescoring approach that considers each decomposition
(i.e. the sub-questions and their answers) to select the best final answer,
greatly improving overall performance. Our experiments on HotpotQA show that
this approach achieves the state-of-the-art results, while providing
explainable evidence for its decision making in the form of sub-questions.