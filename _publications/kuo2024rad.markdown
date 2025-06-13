---
layout: publication
title: 'Rad-bench: Evaluating Large Language Models Capabilities In Retrieval Augmented Dialogues'
authors: Tzu-lin Kuo, Feng-ting Liao, Mu-wei Hsieh, Fu-chieh Chang, Po-chun Hsu, Da-shan Shiu
conference: "Arxiv"
year: 2024
bibkey: kuo2024rad
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12558"}
  - {name: "Code", url: "https://github.com/mtkresearch/RAD-Bench"}
tags: ['RAG', 'Applications', 'Has Code', 'Reinforcement Learning']
---
In real-world applications with Large Language Models (LLMs), external
retrieval mechanisms - such as Search-Augmented Generation (SAG), tool
utilization, and Retrieval-Augmented Generation (RAG) - are often employed to
enhance the quality of augmented generations in dialogues. These approaches
often come with multi-turn dialogue, where each interaction is enriched by
relevant information retrieved from external sources. Existing benchmarks
either assess LLMs' chat abilities in multi-turn dialogues or their use of
retrieval for augmented responses in single-turn settings. However, there is a
gap in evaluating LLMs' ability to leverage retrieval for more precise
responses across multiple turns. To address this limitation, we introduce
RAD-Bench (Retrieval Augmented Dialogue), a benchmark designed to evaluate
LLMs' capabilities in multi-turn dialogues following retrievals, essential for
their deployment in context-rich applications. RAD-Bench evaluates two key
abilities of LLMs: Retrieval Synthesis and Retrieval Reasoning. These are
measured using discriminative questions and retrieved contexts, and
corresponding reference answers, assessing how effectively LLMs integrate and
reason with context to maintain and enhance conversation quality over multiple
turns. Our evaluation results on commonly used LLMs reveal that model
performance deteriorates as additional layers of conditions or constraints are
applied across conversation turns, even when accurate retrieved contexts are
provided. The data and code are available at
https://github.com/mtkresearch/RAD-Bench
