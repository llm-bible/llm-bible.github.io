---
layout: publication
title: What Makes Data-to-Text Generation Hard for Pretrained Language Models
authors: Keymanesh Moniba, Benton Adrian, Dredze Mark
conference: "Arxiv"
year: 2022
bibkey: keymanesh2022what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.11505"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'Training Techniques']
---
Expressing natural language descriptions of structured facts or relations -- data-to-text generation (D2T) -- increases the accessibility of structured knowledge repositories. Previous work shows that pre-trained language models(PLMs) perform remarkably well on this task after fine-tuning on a significant amount of task-specific training data. On the other hand while auto-regressive PLMs can generalize from a few task examples their efficacy at D2T is largely unexplored. Furthermore we have an incomplete understanding of the limits of PLMs on D2T. In this work we conduct an empirical study of both fine-tuned and auto-regressive PLMs on the DART multi-domain D2T dataset. We consider their performance as a function of the amount of task-specific data and how these data are incorporated into the models zero and few-shot learning and fine-tuning of model weights. In addition we probe the limits of PLMs by measuring performance on subsets of the evaluation data novel predicates and abstractive test examples. To improve the performance on these subsets we investigate two techniques providing predicate descriptions in the context and re-ranking generated candidates by information reflected in the source. Finally we conduct a human evaluation of model errors and show that D2T generation tasks would benefit from datasets with more careful manual curation.
