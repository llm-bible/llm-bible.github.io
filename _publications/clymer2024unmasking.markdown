---
layout: publication
title: 'Poser: Unmasking Alignment Faking Llms By Manipulating Their Internals'
authors: Joshua Clymer, Caden Juang, Severin Field
conference: "Arxiv"
year: 2024
bibkey: clymer2024unmasking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05466"}
tags: ['Interpretability and Explainability', 'Reinforcement Learning']
---
Like a criminal under investigation, Large Language Models (LLMs) might
pretend to be aligned while evaluated and misbehave when they have a good
opportunity. Can current interpretability methods catch these 'alignment
fakers?' To answer this question, we introduce a benchmark that consists of 324
pairs of LLMs fine-tuned to select actions in role-play scenarios. One model in
each pair is consistently benign (aligned). The other model misbehaves in
scenarios where it is unlikely to be caught (alignment faking). The task is to
identify the alignment faking model using only inputs where the two models
behave identically. We test five detection strategies, one of which identifies
98% of alignment-fakers.
