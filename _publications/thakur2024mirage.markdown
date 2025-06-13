---
layout: publication
title: 'Mirage-bench: Automatic Multilingual Benchmark Arena For Retrieval-augmented Generation Systems'
authors: Nandan Thakur, Suleman Kazi, Ge Luo, Jimmy Lin, Amin Ahmad
conference: "Arxiv"
year: 2024
bibkey: thakur2024mirage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13716"}
  - {name: "Code", url: "https://github.com/vectara/mirage-bench"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Has Code']
---
Traditional retrieval-augmented generation (RAG) benchmarks evaluate systems
using heuristic-based metrics, but these require human preferences as the
ground truth for reference. In contrast, arena-based benchmarks, where systems
compete against each other, require an expensive large language model (LLM) as
a judge for a reliable evaluation. We present a simple efficient technique to
combine the best of both worlds. The idea is to train a surrogate judge using
heuristic metrics as input, to output the LLM as a judge prediction. In our
work, we develop MIRAGE-Bench, a synthetic arena-based RAG benchmark for 18
diverse languages on Wikipedia focused on multilingual answer generation
evaluation. It extensively couples both heuristic features and LLM as a judge
for evaluation. We benchmark 19 multilingual LLMs, and observe a high
correlation (Kendall Tau (\\(\tau\\)) = 0.909) using our surrogate judge and
between GPT-4o as a teacher using the Bradley-Terry framework. Our results show
proprietary and large open-source LLMs currently dominate on MIRAGE-Bench. Our
code and datasets are made publicly available here:
https://github.com/vectara/mirage-bench.
