---
layout: publication
title: 'Towards Explainable Temporal User Profiling With Llms'
authors: Milad Sabouri, Masoud Mansoury, Kun Lin, Bamshad Mobasher
conference: "Arxiv"
year: 2025
bibkey: sabouri2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00886'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'RAG', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
Accurately modeling user preferences is vital not only for improving
recommendation performance but also for enhancing transparency in recommender
systems. Conventional user profiling methods, such as averaging item
embeddings, often overlook the evolving, nuanced nature of user interests,
particularly the interplay between short-term and long-term preferences. In
this work, we leverage large language models (LLMs) to generate natural
language summaries of users' interaction histories, distinguishing recent
behaviors from more persistent tendencies. Our framework not only models
temporal user preferences but also produces natural language profiles that can
be used to explain recommendations in an interpretable manner. These textual
profiles are encoded via a pre-trained model, and an attention mechanism
dynamically fuses the short-term and long-term embeddings into a comprehensive
user representation. Beyond boosting recommendation accuracy over multiple
baselines, our approach naturally supports explainability: the interpretable
text summaries and attention weights can be exposed to end users, offering
insights into why specific items are suggested. Experiments on real-world
datasets underscore both the performance gains and the promise of generating
clearer, more transparent justifications for content-based recommendations.
