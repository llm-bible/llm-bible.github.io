---
layout: publication
title: 'Towards Lighter And Robust Evaluation For Retrieval Augmented Generation'
authors: Alex-razvan Ispas, Charles-elie Simon, Fabien Caspani, Vincent Guigue
conference: "Arxiv"
year: 2025
bibkey: ispas2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16161"}
tags: ['Model Architecture', 'Tools', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods', 'Prompting']
---
Large Language Models are prompting us to view more NLP tasks from a
generative perspective. At the same time, they offer a new way of accessing
information, mainly through the RAG framework. While there have been notable
improvements for the autoregressive models, overcoming hallucination in the
generated answers remains a continuous problem. A standard solution is to use
commercial LLMs, such as GPT4, to evaluate these algorithms. However, such
frameworks are expensive and not very transparent. Therefore, we propose a
study which demonstrates the interest of open-weight models for evaluating RAG
hallucination. We develop a lightweight approach using smaller, quantized LLMs
to provide an accessible and interpretable metric that gives continuous scores
for the generated answer with respect to their correctness and faithfulness.
This score allows us to question decisions' reliability and explore thresholds
to develop a new AUC metric as an alternative to correlation with human
judgment.
