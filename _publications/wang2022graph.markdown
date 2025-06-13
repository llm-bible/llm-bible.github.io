---
layout: publication
title: 'Graph-based Extractive Explainer For Recommendations'
authors: Peng Wang, Renqin Cai, Hongning Wang
conference: "Arxiv"
year: 2022
bibkey: wang2022graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2202.09730'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Survey Paper']
---
Explanations in a recommender system assist users in making informed
decisions among a set of recommended items. Great research attention has been
devoted to generating natural language explanations to depict how the
recommendations are generated and why the users should pay attention to them.
However, due to different limitations of those solutions, e.g., template-based
or generation-based, it is hard to make the explanations easily perceivable,
reliable and personalized at the same time.
  In this work, we develop a graph attentive neural network model that
seamlessly integrates user, item, attributes, and sentences for
extraction-based explanation. The attributes of items are selected as the
intermediary to facilitate message passing for user-item specific evaluation of
sentence relevance. And to balance individual sentence relevance, overall
attribute coverage, and content redundancy, we solve an integer linear
programming problem to make the final selection of sentences. Extensive
empirical evaluations against a set of state-of-the-art baseline methods on two
benchmark review datasets demonstrated the generation quality of the proposed
solution.
