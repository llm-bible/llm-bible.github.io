---
layout: publication
title: 'One Model For All: Large Language Models Are Domain-agnostic Recommendation Systems'
authors: Zuoli Tang, Zhaoxin Huan, Zihao Li, Xiaolu Zhang, Jun Hu, Chilin Fu, Jun Zhou, Lixin Zou, Chenliang Li
conference: "Arxiv"
year: 2023
bibkey: tang2023one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14304"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Scaling Laws']
---
Sequential recommendation systems aim to predict users' next likely
interaction based on their history. However, these systems face data sparsity
and cold-start problems. Utilizing data from other domains, known as
multi-domain methods, is useful for alleviating these problems. However,
traditional multi-domain methods rely on meaningless ID-based item
representation, which makes it difficult to align items with similar meanings
from different domains, yielding sup-optimal knowledge transfer. This paper
introduces LLM-Rec, a framework that utilizes pre-trained large language models
(LLMs) for domain-agnostic recommendation. Specifically, we mix user's
behaviors from multiple domains and concatenate item titles into a sentence,
then use LLMs for generating user and item representations. By mixing behaviors
across different domains, we can exploit the knowledge encoded in LLMs to
bridge the semantic across over multi-domain behaviors, thus obtaining
semantically rich representations and improving performance in all domains.
Furthermore, we explore the underlying reasons why LLMs are effective and
investigate whether LLMs can understand the semantic correlations as the
recommendation model, and if advanced techniques like scaling laws in NLP also
work in recommendations. We conduct extensive experiments with LLMs ranging
from 40M to 6.7B to answer the above questions and to verify the effectiveness
of LLM-Rec in multi-domain recommendation.
