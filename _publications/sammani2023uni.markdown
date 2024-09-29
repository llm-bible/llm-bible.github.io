---
layout: publication
title: Uni45;nlx Unifying Textual Explanations For Vision And Vision45;language Tasks
authors: Sammani Fawaz, Deligiannis Nikos
conference: "Arxiv"
year: 2023
bibkey: sammani2023uni
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09033"}
  - {name: "Code", url: "https://github.com/fawazsammani/uni&#45;nlx"}
tags: ['Applications', 'Has Code', 'Interpretability And Explainability', 'Language Modeling', 'RAG', 'Tools', 'Training Techniques']
---
Natural Language Explanations (NLE) aim at supplementing the prediction of a model with human45;friendly natural text. Existing NLE approaches involve training separate models for each downstream task. In this work we propose Uni45;NLX a unified framework that consolidates all NLE tasks into a single and compact multi45;task model using a unified training objective of text generation. Additionally we introduce two new NLE datasets 1) ImageNetX a dataset of 144K samples for explaining ImageNet categories and 2) VQA45;ParaX a dataset of 123K samples for explaining the task of Visual Question Answering (VQA). Both datasets are derived leveraging large language models (LLMs). By training on the 1M combined NLE samples our single unified framework is capable of simultaneously performing seven NLE tasks including VQA visual recognition and visual reasoning tasks with 7X fewer parameters demonstrating comparable performance to the independent task45;specific models in previous approaches and in certain tasks even outperforming them. Code is at https://github.com/fawazsammani/uni&#45;nlx
