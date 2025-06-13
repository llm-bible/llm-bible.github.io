---
layout: publication
title: 'Can Models Help Us Create Better Models? Evaluating Llms As Data Scientists'
authors: Michał Pietruszka, Łukasz Borchmann, Aleksander Jędrosz, Paweł Morawiecki
conference: "Arxiv"
year: 2024
bibkey: pietruszka2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23331"}
tags: ['Prompting', 'Reinforcement Learning']
---
We present a benchmark for large language models designed to tackle one of
the most knowledge-intensive tasks in data science: writing feature engineering
code, which requires domain knowledge in addition to a deep understanding of
the underlying problem and data structure. The model is provided with a dataset
description in a prompt and asked to generate code transforming it. The
evaluation score is derived from the improvement achieved by an XGBoost model
fit on the modified dataset compared to the original data. By an extensive
evaluation of state-of-the-art models and comparison to well-established
benchmarks, we demonstrate that the FeatEng of our proposal can cheaply and
efficiently assess the broad capabilities of LLMs, in contrast to the existing
methods.
