---
layout: publication
title: 'MAPLE: Enhancing Review Generation With Multi-aspect Prompt Learning In Explainable Recommendation'
authors: Yang Ching-wen, Chen Che Wei, Wu Kun-da, Xu Hao, Yao Jui-feng, Kao Hung-yu
conference: "Arxiv"
year: 2024
bibkey: yang2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09865"}
tags: ['Interpretability And Explainability', 'Prompting', 'Reinforcement Learning', 'Survey Paper', 'Tools']
---
Explainable Recommendation task is designed to receive a pair of user and
item and output explanations to justify why an item is recommended to a user.
Many models treat review-generation as a proxy of explainable recommendation.
Although they are able to generate fluent and grammatical sentences, they
suffer from generality and hallucination issues. We propose a personalized,
aspect-controlled model called Multi-Aspect Prompt LEarner (MAPLE), in which it
integrates aspect category as another input dimension to facilitate the
memorization of fine-grained aspect terms. Experiments on two real-world review
datasets in restaurant domain show that MAPLE outperforms the baseline
review-generation models in terms of text and feature diversity while
maintaining excellent coherence and factual relevance. We further treat MAPLE
as a retriever component in the retriever-reader framework and employ a
Large-Language Model (LLM) as the reader, showing that MAPLE's explanation
along with the LLM's comprehension ability leads to enriched and personalized
explanation as a result. We will release the code and data in this http upon
acceptance.
