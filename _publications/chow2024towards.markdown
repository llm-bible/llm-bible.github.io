---
layout: publication
title: 'Towards Time Series Reasoning With Llms'
authors: Winnie Chow, Lauren Gardiner, Haraldur T. Hallgrímsson, Maxwell A. Xu, Shirley You Ren
conference: "Arxiv"
year: 2024
bibkey: chow2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11376"}
tags: ['RAG', 'Model Architecture', 'GPT']
---
Multi-modal large language models (MLLMs) have enabled numerous advances in
understanding and reasoning in domains like vision, but we have not yet seen
this broad success for time-series. Although prior works on time-series MLLMs
have shown promising performance in time-series forecasting, very few works
show how an LLM could be used for time-series reasoning in natural language. We
propose a novel multi-modal time-series LLM approach that learns generalizable
information across various domains with powerful zero-shot performance. First,
we train a lightweight time-series encoder on top of an LLM to directly extract
time-series information. Then, we fine-tune our model with chain-of-thought
augmented time-series tasks to encourage the model to generate reasoning paths.
We show that our model learns a latent representation that reflects specific
time-series features (e.g. slope, frequency), as well as outperforming GPT-4o
on a set of zero-shot reasoning tasks on a variety of domains.
