---
layout: publication
title: 'Compression Represents Intelligence Linearly'
authors: Yuzhen Huang, Jinghan Zhang, Zifei Shan, Junxian He
conference: "Arxiv"
year: 2024
bibkey: huang2024compression
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.09937'}
tags: ['Reinforcement Learning', 'RAG', 'Language Modeling', 'Efficiency and Optimization']
---
There is a belief that learning to compress well will lead to intelligence.
Recently, language modeling has been shown to be equivalent to compression,
which offers a compelling rationale for the success of large language models
(LLMs): the development of more advanced language models is essentially
enhancing compression which facilitates intelligence. Despite such appealing
discussions, little empirical evidence is present for the interplay between
compression and intelligence. In this work, we examine their relationship in
the context of LLMs, treating LLMs as data compressors. Given the abstract
concept of "intelligence", we adopt the average downstream benchmark scores as
a surrogate, specifically targeting intelligence related to knowledge and
commonsense, coding, and mathematical reasoning. Across 12 benchmarks, our
study brings together 31 public LLMs that originate from diverse organizations.
Remarkably, we find that LLMs' intelligence -- reflected by average benchmark
scores -- almost linearly correlates with their ability to compress external
text corpora. These results provide concrete evidence supporting the belief
that superior compression indicates greater intelligence. Furthermore, our
findings suggest that compression efficiency, as an unsupervised metric derived
from raw text corpora, serves as a reliable evaluation measure that is linearly
associated with the model capabilities. We open-source our compression datasets
as well as our data collection pipelines to facilitate future researchers to
assess compression properly.
