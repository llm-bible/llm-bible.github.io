---
layout: publication
title: 'Beyond Retrieval: Generating Narratives In Conversational Recommender Systems'
authors: Krishna Sayana, Raghavendra Vasudeva, Yuri Vasilevski, Kun Su, Liam Hebert, James Pine, Hubert Pham, Ambarish Jash, Sukhdeep Sodhi
conference: "Arxiv"
year: 2024
bibkey: sayana2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16780"}
tags: ['Interpretability and Explainability', 'Model Architecture', 'Merging', 'Reinforcement Learning', 'RecSys']
---
The recent advances in Large Language Model's generation and reasoning
capabilities present an opportunity to develop truly conversational
recommendation systems. However, effectively integrating recommender system
knowledge into LLMs for natural language generation which is tailored towards
recommendation tasks remains a challenge. This paper addresses this challenge
by making two key contributions.
  First, we introduce a new dataset (REGEN) for natural language generation
tasks in conversational recommendations. REGEN (Reviews Enhanced with
GEnerative Narratives) extends the Amazon Product Reviews dataset with rich
user narratives, including personalized explanations of product preferences,
product endorsements for recommended items, and summaries of user purchase
history. REGEN is made publicly available to facilitate further research.
Furthermore, we establish benchmarks using well-known generative metrics, and
perform an automated evaluation of the new dataset using a rater LLM. Second,
the paper introduces a fusion architecture (CF model with an LLM) which serves
as a baseline for REGEN. And to the best of our knowledge, represents the first
attempt to analyze the capabilities of LLMs in understanding recommender
signals and generating rich narratives. We demonstrate that LLMs can
effectively learn from simple fusion architectures utilizing interaction-based
CF embeddings, and this can be further enhanced using the metadata and
personalization data associated with items. Our experiments show that combining
CF and content embeddings leads to improvements of 4-12% in key language
metrics compared to using either type of embedding individually. We also
provide an analysis to interpret how CF and content embeddings contribute to
this new generative task.
