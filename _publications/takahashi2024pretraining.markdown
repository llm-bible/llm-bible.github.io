---
layout: publication
title: 'Pretraining And Updates Of Domain-specific LLM: A Case Study In The Japanese Business Domain'
authors: Kosuke Takahashi, Takahiro Omi, Kosuke Arima, Tatsuya Ishigaki
conference: "Arxiv"
year: 2024
bibkey: takahashi2024pretraining
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.08262'}
tags: ['Reinforcement Learning', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
The development of Large Language Models (LLMs) in various languages has been
advancing, but the combination of non-English languages with domain-specific
contexts remains underexplored. This paper presents our findings from training
and evaluating a Japanese business domain-specific LLM designed to better
understand business-related documents, such as the news on current affairs,
technical reports, and patents. Additionally, LLMs in this domain require
regular updates to incorporate the most recent knowledge. Therefore, we also
report our findings from the first experiments and evaluations involving
updates to this LLM using the latest article data, which is an important
problem setting that has not been addressed in previous research. From our
experiments on a newly created benchmark dataset for question answering in the
target domain, we found that (1) our pretrained model improves QA accuracy
without losing general knowledge, and (2) a proper mixture of the latest and
older texts in the training data for the update is necessary. Our pretrained
model and business domain benchmark are publicly available to support further
studies.
