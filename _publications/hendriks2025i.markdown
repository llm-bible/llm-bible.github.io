---
layout: publication
title: 'Honey, I Shrunk The Language Model: Impact Of Knowledge Distillation Methods On Performance And Explainability'
authors: Daniel Hendriks, Philipp Spitzer, Niklas Kühl, Gerhard Satzger
conference: "Arxiv"
year: 2025
bibkey: hendriks2025i
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.16056'}
tags: ['Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Merging', 'Prompting', 'Interpretability']
---
Artificial Intelligence (AI) has increasingly influenced modern society,
recently in particular through significant advancements in Large Language
Models (LLMs). However, high computational and storage demands of LLMs still
limit their deployment in resource-constrained environments. Knowledge
distillation addresses this challenge by training a small student model from a
larger teacher model. Previous research has introduced several distillation
methods for both generating training data and for training the student model.
Despite their relevance, the effects of state-of-the-art distillation methods
on model performance and explainability have not been thoroughly investigated
and compared. In this work, we enlarge the set of available methods by applying
critique-revision prompting to distillation for data generation and by
synthesizing existing methods for training. For these methods, we provide a
systematic comparison based on the widely used Commonsense Question-Answering
(CQA) dataset. While we measure performance via student model accuracy, we
employ a human-grounded study to evaluate explainability. We contribute new
distillation methods and their comparison in terms of both performance and
explainability. This should further advance the distillation of small language
models and, thus, contribute to broader applicability and faster diffusion of
LLM technology.
