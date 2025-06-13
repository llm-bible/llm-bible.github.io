---
layout: publication
title: 'The Accuracy Paradox In RLHF: When Better Reward Models Don''t Yield Better Language Models'
authors: Yanjun Chen, Dawei Zhu, Yirong Sun, Xinghao Chen, Wei Zhang, Xiaoyu Shen
conference: "Arxiv"
year: 2024
bibkey: chen2024accuracy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.06554'}
  - {name: "Code", url: 'https://github.com/EIT-NLP/AccuracyParadox-RLHF'}
tags: ['Reinforcement Learning', 'Agentic', 'Has Code', 'Training Techniques']
---
Reinforcement Learning from Human Feedback significantly enhances Natural
Language Processing by aligning language models with human expectations. A
critical factor in this alignment is the strength of reward models used during
training. This study explores whether stronger reward models invariably lead to
better language models. In this paper, through experiments on relevance,
factuality, and completeness tasks using the QA-FEEDBACK dataset and reward
models based on Longformer, we uncover a surprising paradox: language models
trained with moderately accurate reward models outperform those guided by
highly accurate ones. This challenges the widely held belief that stronger
reward models always lead to better language models, and opens up new avenues
for future research into the key factors driving model performance and how to
choose the most suitable reward models. Code and additional details are
available at https://github.com/EIT-NLP/AccuracyParadox-RLHF.
