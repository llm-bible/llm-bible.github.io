---
layout: publication
title: 'Confidence Improves Self-consistency In Llms'
authors: Amir Taubenfeld, Tom Sheffer, Eran Ofek, Amir Feder, Ariel Goldstein, Zorik Gekhman, Gal Yona
conference: "Arxiv"
year: 2025
bibkey: taubenfeld2025confidence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06233"}
tags: ['RAG', 'Reinforcement Learning']
---
Self-consistency decoding enhances LLMs' performance on reasoning tasks by
sampling diverse reasoning paths and selecting the most frequent answer.
However, it is computationally expensive, as sampling many of these (lengthy)
paths is required to increase the chances that the correct answer emerges as
the most frequent one. To address this, we introduce Confidence-Informed
Self-Consistency (CISC). CISC performs a weighted majority vote based on
confidence scores obtained directly from the model. By prioritizing
high-confidence paths, it can identify the correct answer with a significantly
smaller sample size. When tested on nine models and four datasets, CISC
outperforms self-consistency in nearly all configurations, reducing the
required number of reasoning paths by over 40% on average. In addition, we
introduce the notion of within-question confidence evaluation, after showing
that standard evaluation methods are poor predictors of success in
distinguishing correct and incorrect answers to the same question. In fact, the
most calibrated confidence method proved to be the least effective for CISC.
Lastly, beyond these practical implications, our results and analyses show that
LLMs can effectively judge the correctness of their own outputs, contributing
to the ongoing debate on this topic.
