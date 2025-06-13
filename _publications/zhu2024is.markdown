---
layout: publication
title: 'Is Your LLM Outdated? A Deep Look At Temporal Generalization'
authors: Chenghao Zhu, Nuo Chen, Yufei Gao, Yunyi Zhang, Prayag Tiwari, Benyou Wang
conference: "Arxiv"
year: 2024
bibkey: zhu2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.08460"}
  - {name: "Code", url: "https://github.com/FreedomIntelligence/FreshBench"}
tags: ['Ethics and Bias', 'Has Code', 'Tools']
---
The rapid advancement of Large Language Models (LLMs) has led to the
development of benchmarks that consider temporal dynamics, however, there
remains a gap in understanding how well these models can generalize across
temporal contexts due to the inherent dynamic nature of language and
information. This paper introduces the concept of temporal generalization in
LLMs, including bias in past and future generalizations. Then we introduce
FreshBench, a new evaluation framework that employs fresh text and event
prediction for assessing LLMs' temporal adaptability, ensuring the evaluation
process free from data leakage and subjective bias. The experiment shows
significant temporal biases and a decline in performance over time. Our
findings reveal that powerful models, while initially superior, tend to decline
more rapidly in future generalization. Additionally, powerful open-source
models demonstrate better long-term adaptability compared to their
closed-source counterparts. Our code is available at
https://github.com/FreedomIntelligence/FreshBench.
