---
layout: publication
title: 'Consens: Assessing Context Grounding In Open-book Question Answering'
authors: Ivan Vankov, Matyo Ivanov, Adriana Correia, Victor Botev
conference: "Arxiv"
year: 2025
bibkey: vankov2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00065"}
tags: ['Ethics and Bias', 'Applications']
---
Large Language Models (LLMs) have demonstrated considerable success in
open-book question answering (QA), where the task requires generating answers
grounded in a provided external context. A critical challenge in open-book QA
is to ensure that model responses are based on the provided context rather than
its parametric knowledge, which can be outdated, incomplete, or incorrect.
Existing evaluation methods, primarily based on the LLM-as-a-judge approach,
face significant limitations, including biases, scalability issues, and
dependence on costly external systems. To address these challenges, we propose
a novel metric that contrasts the perplexity of the model response under two
conditions: when the context is provided and when it is not. The resulting
score quantifies the extent to which the model's answer relies on the provided
context. The validity of this metric is demonstrated through a series of
experiments that show its effectiveness in identifying whether a given answer
is grounded in the provided context. Unlike existing approaches, this metric is
computationally efficient, interpretable, and adaptable to various use cases,
offering a scalable and practical solution to assess context utilization in
open-book QA systems.
