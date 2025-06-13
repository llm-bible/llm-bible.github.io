---
layout: publication
title: 'Improving Conversational Recommender System Via Contextual And Time-aware Modeling With Less Domain-specific Knowledge'
authors: Lingzhi Wang, Shafiq Joty, Wei Gao, Xingshan Zeng, Kam-fai Wong
conference: "Arxiv"
year: 2022
bibkey: wang2022improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.11386"}
tags: ['RecSys', 'Model Architecture', 'Merging', 'Attention Mechanism']
---
Conversational Recommender Systems (CRS) has become an emerging research
topic seeking to perform recommendations through interactive conversations,
which generally consist of generation and recommendation modules. Prior work on
CRS tends to incorporate more external and domain-specific knowledge like item
reviews to enhance performance. Despite the fact that the collection and
annotation of the external domain-specific information needs much human effort
and degenerates the generalizability, too much extra knowledge introduces more
difficulty to balance among them. Therefore, we propose to fully discover and
extract internal knowledge from the context. We capture both entity-level and
contextual-level representations to jointly model user preferences for the
recommendation, where a time-aware attention is designed to emphasize the
recently appeared items in entity-level representations. We further use the
pre-trained BART to initialize the generation module to alleviate the data
scarcity and enhance the context modeling. In addition to conducting
experiments on a popular dataset (ReDial), we also include a multi-domain
dataset (OpenDialKG) to show the effectiveness of our model. Experiments on
both datasets show that our model achieves better performance on most
evaluation metrics with less external knowledge and generalizes well to other
domains. Additional analyses on the recommendation and generation tasks
demonstrate the effectiveness of our model in different scenarios.
