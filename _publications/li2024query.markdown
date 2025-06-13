---
layout: publication
title: 'Quickllama: Query-aware Inference Acceleration For Large Language Models'
authors: Jingyao Li, Han Shi, Xin Jiang, Zhenguo Li, Hong Xu, Jiaya Jia
conference: "Arxiv"
year: 2024
bibkey: li2024query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07528"}
  - {name: "Code", url: "https://github.com/dvlab-research/Q-LLM"}
tags: ['Training Techniques', 'Has Code']
---
The capacity of Large Language Models (LLMs) to comprehend and reason over
long contexts is pivotal for advancements in diverse fields. Yet, they still
stuggle with capturing long-distance dependencies within sequences to deeply
understand semantics. To address this issue, we introduce Query-aware Inference
for LLMs (Q-LLM), a system designed to process extensive sequences akin to
human cognition. By focusing on memory data relevant to a given query, Q-LLM
can accurately capture pertinent information within a fixed window size and
provide precise answers to queries. It doesn't require extra training and can
be seamlessly integrated with any LLMs. Q-LLM using LLaMA3 (QuickLLaMA) can
read Harry Potter within 30s and accurately answer the questions. On widely
recognized benchmarks, Q-LLM improved by 7.17% compared to the current
state-of-the-art on LLaMA3, and by 3.26% on Mistral on the \\(\infty\\)-bench. In
the Needle-in-a-Haystack and BABILong task, Q-LLM improved upon the current
SOTA by 7.0% and 6.1%. Our code can be found in
https://github.com/dvlab-research/Q-LLM.
