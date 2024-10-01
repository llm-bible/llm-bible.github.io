---
layout: publication
title: 'The ICL Consistency Test'
authors: Weber Lucas, Bruni Elia, Hupkes Dieuwke
conference: "Arxiv"
year: 2023
bibkey: weber2023icl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04945"}
tags: ['Prompting']
---
Just like the previous generation of task-tuned models, large language models (LLMs) that are adapted to tasks via prompt-based methods like in-context-learning (ICL) perform well in some setups but not in others. This lack of consistency in prompt-based learning hints at a lack of robust generalisation. We here introduce the ICL consistency test -- a contribution to the GenBench collaborative benchmark task (CBT) -- which evaluates how consistent a model makes predictions across many different setups while using the same data. The test is based on different established natural language inference tasks. We provide preprocessed data constituting 96 different 'setups' and a metric that estimates model consistency across these setups. The metric is provided on a fine-grained level to understand what properties of a setup render predictions unstable and on an aggregated level to compare overall model consistency. We conduct an empirical analysis of eight state-of-the-art models, and our consistency metric reveals how all tested LLMs lack robust generalisation.
