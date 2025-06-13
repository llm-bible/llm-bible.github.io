---
layout: publication
title: 'STEPS: A Benchmark For Order Reasoning In Sequential Tasks'
authors: Weizhi Wang, Hong Wang, Xifeng Yan
conference: "Arxiv"
year: 2023
bibkey: wang2023benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.04441"}
tags: ['Few-Shot', 'Agentic', 'Prompting', 'In-Context Learning']
---
Various human activities can be abstracted into a sequence of actions in
natural text, i.e. cooking, repairing, manufacturing, etc. Such action
sequences heavily depend on the executing order, while disorder in action
sequences leads to failure of further task execution by robots or AI agents.
Therefore, to verify the order reasoning capability of current neural models in
sequential tasks, we propose a challenging benchmark , named STEPS. STEPS
involves two subtask settings, focusing on determining the rationality of given
next step in recipes and selecting the reasonable step from the multi-choice
question, respectively. We describe the data construction and task
formulations, and benchmark most of significant Large Language Models (LLMs).
The experimental results demonstrate 1) The commonsense reasoning of action
orders in sequential tasks are challenging to resolve via zero-shot prompting
or few-shot in-context learning for LLMs; 2) Prompting method still
significantly lags behind tuning-based method on STEPS.
