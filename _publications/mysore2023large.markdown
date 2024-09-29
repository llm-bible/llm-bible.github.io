---
layout: publication
title: Large Language Model Augmented Narrative Driven Recommendations
authors: Mysore Sheshera, Mccallum Andrew, Zamani Hamed
conference: "Arxiv"
year: 2023
bibkey: mysore2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.02250"}
tags: ['Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Narrative45;driven recommendation (NDR) presents an information access problem where users solicit recommendations with verbose descriptions of their preferences and context for example travelers soliciting recommendations for points of interest while describing their likes/dislikes and travel circumstances. These requests are increasingly important with the rise of natural language45;based conversational interfaces for search and recommendation systems. However NDR lacks abundant training data for models and current platforms commonly do not support these requests. Fortunately classical user45;item interaction datasets contain rich textual data e.g. reviews which often describe user preferences and context 45; this may be used to bootstrap training for NDR models. In this work we explore using large language models (LLMs) for data augmentation to train NDR models. We use LLMs for authoring synthetic narrative queries from user45;item interactions with few45;shot prompting and train retrieval models for NDR on synthetic queries and user45;item interaction data. Our experiments demonstrate that this is an effective strategy for training small45;parameter retrieval models that outperform other retrieval and LLM baselines for narrative45;driven recommendation.
