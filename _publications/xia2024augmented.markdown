---
layout: publication
title: 'Aprompt4em: Augmented Prompt Tuning For Generalized Entity Matching'
authors: Yikuan Xia, Jiazun Chen, Xinchi Li, Jun Gao
conference: "Arxiv"
year: 2024
bibkey: xia2024augmented
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.04820'}
tags: ['RAG', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Generalized Entity Matching (GEM), which aims at judging whether two records
represented in different formats refer to the same real-world entity, is an
essential task in data management. The prompt tuning paradigm for pre-trained
language models (PLMs), including the recent PromptEM model, effectively
addresses the challenges of low-resource GEM in practical applications,
offering a robust solution when labeled data is scarce. However, existing
prompt tuning models for GEM face the challenges of prompt design and
information gap. This paper introduces an augmented prompt tuning framework for
the challenges, which consists of two main improvements. The first is an
augmented contextualized soft token-based prompt tuning method that extracts a
guiding soft token benefit for the PLMs' prompt tuning, and the second is a
cost-effective information augmentation strategy leveraging large language
models (LLMs). Our approach performs well on the low-resource GEM challenges.
Extensive experiments show promising advancements of our basic model without
information augmentation over existing methods based on moderate-size PLMs
(average 5.24%+), and our model with information augmentation achieves
comparable performance compared with fine-tuned LLMs, using less than 14% of
the API fee.
