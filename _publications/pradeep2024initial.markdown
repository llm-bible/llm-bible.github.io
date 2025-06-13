---
layout: publication
title: 'Initial Nugget Evaluation Results For The TREC 2024 RAG Track With The Autonuggetizer Framework'
authors: Ronak Pradeep, Nandan Thakur, Shivani Upadhyay, Daniel Campos, Nick Craswell, Jimmy Lin
conference: "Arxiv"
year: 2024
bibkey: pradeep2024initial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.09607"}
tags: ['RAG', 'Tools', 'Applications']
---
This report provides an initial look at partial results from the TREC 2024
Retrieval-Augmented Generation (RAG) Track. We have identified RAG evaluation
as a barrier to continued progress in information access (and more broadly,
natural language processing and artificial intelligence), and it is our hope
that we can contribute to tackling the many challenges in this space. The
central hypothesis we explore in this work is that the nugget evaluation
methodology, originally developed for the TREC Question Answering Track in
2003, provides a solid foundation for evaluating RAG systems. As such, our
efforts have focused on "refactoring" this methodology, specifically applying
large language models to both automatically create nuggets and to automatically
assign nuggets to system answers. We call this the AutoNuggetizer framework.
Within the TREC setup, we are able to calibrate our fully automatic process
against a manual process whereby nuggets are created by human assessors
semi-manually and then assigned manually to system answers. Based on initial
results across 21 topics from 45 runs, we observe a strong correlation between
scores derived from a fully automatic nugget evaluation and a (mostly) manual
nugget evaluation by human assessors. This suggests that our fully automatic
evaluation process can be used to guide future iterations of RAG systems.
