---
layout: publication
title: 'Back To The Future: Towards Explainable Temporal Reasoning With Large Language Models'
authors: Chenhan Yuan, Qianqian Xie, Jimin Huang, Sophia Ananiadou
conference: "Arxiv"
year: 2023
bibkey: yuan2023back
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01074"}
tags: ['Fine-Tuning', 'Applications', 'Interpretability and Explainability', 'Reinforcement Learning', 'Interpretability']
---
Temporal reasoning is a crucial NLP task, providing a nuanced understanding
of time-sensitive contexts within textual data. Although recent advancements in
LLMs have demonstrated their potential in temporal reasoning, the predominant
focus has been on tasks such as temporal expression and temporal relation
extraction. These tasks are primarily designed for the extraction of direct and
past temporal cues and to engage in simple reasoning processes. A significant
gap remains when considering complex reasoning tasks such as event forecasting,
which requires multi-step temporal reasoning on events and prediction on the
future timestamp. Another notable limitation of existing methods is their
incapability to provide an illustration of their reasoning process, hindering
explainability. In this paper, we introduce the first task of explainable
temporal reasoning, to predict an event's occurrence at a future timestamp
based on context which requires multiple reasoning over multiple events, and
subsequently provide a clear explanation for their prediction. Our task offers
a comprehensive evaluation of both the LLMs' complex temporal reasoning
ability, the future event prediction ability, and explainability-a critical
attribute for AI applications. To support this task, we present the first
multi-source instruction-tuning dataset of explainable temporal reasoning
(ExpTime) with 26k derived from the temporal knowledge graph datasets and their
temporal reasoning paths, using a novel knowledge-graph-instructed-generation
strategy. Based on the dataset, we propose the first open-source LLM series
TimeLlaMA based on the foundation LlaMA2, with the ability of instruction
following for explainable temporal reasoning. We compare the performance of our
method and a variety of LLMs, where our method achieves the state-of-the-art
performance of temporal prediction and explanation.
