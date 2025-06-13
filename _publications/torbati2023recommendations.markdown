---
layout: publication
title: 'Recommendations By Concise User Profiles From Review Text'
authors: Ghazaleh Haratinezhad Torbati, Anna Tigunova, Andrew Yates, Gerhard Weikum
conference: "Arxiv"
year: 2023
bibkey: torbati2023recommendations
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01314"}
tags: ['Training Techniques', 'Model Architecture', 'Survey Paper', 'Tools', 'RecSys', 'Pretraining Methods', 'Fine-Tuning', 'Transformer']
---
Recommender systems perform well for popular items and users with ample
interactions (likes, ratings etc.). This work addresses the difficult and
underexplored case of users who have very sparse interactions but post
informative review texts. This setting naturally calls for encoding
user-specific text with large language models (LLM). However, feeding the full
text of all reviews through an LLM has a weak signal-to-noise ratio and incurs
high costs of processed tokens. This paper addresses these two issues. It
presents a light-weight framework, called CUP, which first computes concise
user profiles and feeds only these into the training of transformer-based
recommenders. For user profiles, we devise various techniques to select the
most informative cues from noisy reviews. Experiments, with book reviews data,
show that fine-tuning a small language model with judiciously constructed
profiles achieves the best performance, even in comparison to LLM-generated
rankings.
