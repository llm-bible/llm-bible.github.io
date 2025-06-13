---
layout: publication
title: 'Large Language Models Engineer Too Many Simple Features For Tabular Data'
authors: Jaris Küken, Lennart Purucker, Frank Hutter
conference: "Arxiv"
year: 2024
bibkey: küken2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17787"}
tags: ['Language Modeling', 'Tools', 'Ethics and Bias', 'Applications']
---
Tabular machine learning problems often require time-consuming and
labor-intensive feature engineering. Recent efforts have focused on using large
language models (LLMs) to capitalize on their potential domain knowledge. At
the same time, researchers have observed ethically concerning negative biases
in other LLM-related use cases, such as text generation. These developments
motivated us to investigate whether LLMs exhibit a bias that negatively impacts
the performance of feature engineering. While not ethically concerning, such a
bias could hinder practitioners from fully utilizing LLMs for automated data
science. Therefore, we propose a method to detect potential biases by detecting
anomalies in the frequency of operators (e.g., adding two features) suggested
by LLMs when engineering new features. Our experiments evaluate the bias of
four LLMs, two big frontier and two small open-source models, across 27 tabular
datasets. Our results indicate that LLMs are biased toward simple operators,
such as addition, and can fail to utilize more complex operators, such as
grouping followed by aggregations. Furthermore, the bias can negatively impact
the predictive performance when using LLM-generated features. Our results call
for mitigating bias when using LLMs for feature engineering.
