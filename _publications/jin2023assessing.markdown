---
layout: publication
title: 'Cladder: Assessing Causal Reasoning In Language Models'
authors: Zhijing Jin, Yuen Chen, Felix Leeb, Luigi Gresele, Ojasv Kamal, Zhiheng Lyu, Kevin Blin, Fernando Gonzalez Adauto, Max Kleiman-weiner, Mrinmaya Sachan, Bernhard Schölkopf
conference: "Arxiv"
year: 2023
bibkey: jin2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04350"}
  - {name: "Code", url: "https://huggingface.co/datasets/causalNLP/cladder,"}
  - {name: "Code", url: "https://github.com/causalNLP/cladder"}
tags: ['Prompting', 'Has Code', 'ACL', 'Reinforcement Learning']
---
The ability to perform causal reasoning is widely considered a core feature
of intelligence. In this work, we investigate whether large language models
(LLMs) can coherently reason about causality. Much of the existing work in
natural language processing (NLP) focuses on evaluating commonsense causal
reasoning in LLMs, thus failing to assess whether a model can perform causal
inference in accordance with a set of well-defined formal rules. To address
this, we propose a new NLP task, causal inference in natural language, inspired
by the "causal inference engine" postulated by Judea Pearl et al. We compose a
large dataset, CLadder, with 10K samples: based on a collection of causal
graphs and queries (associational, interventional, and counterfactual), we
obtain symbolic questions and ground-truth answers, through an oracle causal
inference engine. These are then translated into natural language. We evaluate
multiple LLMs on our dataset, and we introduce and evaluate a bespoke
chain-of-thought prompting strategy, CausalCoT. We show that our task is highly
challenging for LLMs, and we conduct an in-depth analysis to gain deeper
insights into the causal reasoning abilities of LLMs. Our data is open-sourced
at https://huggingface.co/datasets/causalNLP/cladder, and our code can be found
at https://github.com/causalNLP/cladder.
