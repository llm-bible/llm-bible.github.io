---
layout: publication
title: 'REGEN: A Dataset And Benchmarks With Natural Language Critiques And Narratives'
authors: Kun Su, Krishna Sayana, Hubert Pham, James Pine, Yuri Vasilevski, Raghavendra Vasudeva, Marialena Kyriakidi, Liam Hebert, Ambarish Jash, Anushya Subbiah, Sukhdeep Sodhi
conference: "Arxiv"
year: 2025
bibkey: su2025dataset
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.11924'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Tools']
---
This paper introduces a novel dataset REGEN (Reviews Enhanced with GEnerative
Narratives), designed to benchmark the conversational capabilities of
recommender Large Language Models (LLMs), addressing the limitations of
existing datasets that primarily focus on sequential item prediction. REGEN
extends the Amazon Product Reviews dataset by inpainting two key natural
language features: (1) user critiques, representing user "steering" queries
that lead to the selection of a subsequent item, and (2) narratives, rich
textual outputs associated with each recommended item taking into account prior
context. The narratives include product endorsements, purchase explanations,
and summaries of user preferences.
  Further, we establish an end-to-end modeling benchmark for the task of
conversational recommendation, where models are trained to generate both
recommendations and corresponding narratives conditioned on user history (items
and critiques). For this joint task, we introduce a modeling framework LUMEN
(LLM-based Unified Multi-task Model with Critiques, Recommendations, and
Narratives) which uses an LLM as a backbone for critiquing, retrieval and
generation. We also evaluate the dataset's quality using standard auto-rating
techniques and benchmark it by training both traditional and LLM-based
recommender models. Our results demonstrate that incorporating critiques
enhances recommendation quality by enabling the recommender to learn language
understanding and integrate it with recommendation signals. Furthermore, LLMs
trained on our dataset effectively generate both recommendations and contextual
narratives, achieving performance comparable to state-of-the-art recommenders
and language models.
