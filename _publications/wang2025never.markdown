---
layout: publication
title: 'Never Start From Scratch: Expediting On-device LLM Personalization Via Explainable Model Selection'
authors: Haoming Wang, Boyuan Yang, Xiangyu Yin, Wei Gao
conference: "in Proceedings of the 23rd ACM International Conference on Mobile Systems Applications and Services (MobiSys) 2025"
year: 2025
bibkey: wang2025never
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13938"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Interpretability and Explainability', 'Applications']
---
Personalization of Large Language Models (LLMs) is important in practical
applications to accommodate the individual needs of different mobile users. Due
to data privacy concerns, LLM personalization often needs to be locally done at
the user's mobile device, but such on-device personalization is constrained by
both the limitation of on-device compute power and insufficiency of user's
personal data. In this paper, we address these constraints by fine-tuning an
already personalized LLM with user's personal data, and present XPerT, a new
technique that ensure proper selection of such already personalized LLMs based
on explainability about how they were being fine-tuned. We implemented and
evaluated XPerT on various smartphone models with mainstream LLMs, and
experiment results show that XPerT reduces the computation costs of on-device
LLM personalization by 83%, and improves its data efficiency by 51%.
