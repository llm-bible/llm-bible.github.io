---
layout: publication
title: 'DIMSUM: Discourse In Mathematical Reasoning As A Supervision Module'
authors: Krish Sharma, Niyar R Barman, Akshay Chaturvedi, Nicholas Asher
conference: "Arxiv"
year: 2025
bibkey: sharma2025discourse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04685"}
tags: ['Training Techniques', 'Pretraining Methods']
---
We look at reasoning on GSM8k, a dataset of short texts presenting primary
school, math problems. We find, with Mirzadeh et al. (2024), that current LLM
progress on the data set may not be explained by better reasoning but by
exposure to a broader pretraining data distribution. We then introduce a novel
information source for helping models with less data or inferior training
reason better: discourse structure. We show that discourse structure improves
performance for models like Llama2 13b by up to 160%. Even for models that have
most likely memorized the data set, adding discourse structural information to
the model still improves predictions and dramatically improves large model
performance on out of distribution examples.
