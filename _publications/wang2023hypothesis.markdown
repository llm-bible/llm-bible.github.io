---
layout: publication
title: Hypothesis Search\: Inductive Reasoning With Language Models
authors: Wang Ruocheng, Zelikman Eric, Poesia Gabriel, Pu Yewen, Haber Nick, Goodman Noah D.
conference: "Arxiv"
year: 2023
bibkey: wang2023hypothesis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.05660"}
tags: ['Prompting', 'Reinforcement Learning']
---
Inductive reasoning is a core problem-solving capacity humans can identify underlying principles from a few examples which robustly generalize to novel scenarios. Recent work evaluates large language models (LLMs) on inductive reasoning tasks by directly prompting them yielding in context learning. This works well for straightforward inductive tasks but performs poorly on complex tasks such as the Abstraction and Reasoning Corpus (ARC). In this work we propose to improve the inductive reasoning ability of LLMs by generating explicit hypotheses at multiple levels of abstraction we prompt the LLM to propose multiple abstract hypotheses about the problem in natural language then implement the natural language hypotheses as concrete Python programs. These programs can be verified by running on observed examples and generalized to novel inputs. To reduce the hypothesis search space we explore steps to filter the set of hypotheses to implement we either ask the LLM to summarize them into a smaller set of hypotheses or ask human annotators to select a subset. We verify our pipelines effectiveness on the ARC visual inductive reasoning benchmark its variant 1D-ARC string transformation dataset SyGuS and list transformation dataset List Functions. On a random 100-problem subset of ARC our automated pipeline using LLM summaries achieves 3037; accuracy outperforming the direct prompting baseline (accuracy of 1737;). With the minimal human input of selecting from LLM-generated candidates performance is boosted to 3337;. Our ablations show that both abstract hypothesis generation and concrete program representations benefit LLMs on inductive reasoning tasks.
