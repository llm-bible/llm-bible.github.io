---
layout: publication
title: 'An Actor-critic Approach To Boosting Text-to-sql Large Language Model'
authors: Ziyang Zheng, Haipeng Jing, Canyu Rui, Askar Hamdulla, Dong Wang
conference: "Arxiv"
year: 2024
bibkey: zheng2024actor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22082"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
Text-To-SQL (T2S) conversion based on large language models (LLMs) has found
a wide range of applications, by leveraging the capabilities of LLMs in
interpreting the query intent expressed in natural language. Existing research
focuses on suitable representations for data schema and/or questions,
task-specific instructions and representative examples, and complicated
inference pipelines. All these methods are empirical and task specific, without
a theoretical bound on performance. In this paper, we propose a simple,
general, and performance guaranteed T2S enhancement approach called
Actor-Critic (AC). Specifically, we design two roles using the same LLM: an
Actor to produce SQL queries and a Critic to evaluate the produced SQL. If the
Critic believes the produced SQL is wrong, it notifies the Actor to reproduce
the SQL and perform evaluation again. By this simple iterative process,
expected performance can be derived in theory. We conducted extensive
experiments on the Spider and related datasets with eleven LLMs, and
demonstrated that the Actor-Critic method consistently improves the performance
of T2S, thus serving as a general enhancement approach for T2S conversion.
