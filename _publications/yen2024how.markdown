---
layout: publication
title: 'HELMET: How To Evaluate Long-context Language Models Effectively And Thoroughly'
authors: Howard Yen, Tianyu Gao, Minmin Hou, Ke Ding, Daniel Fleischer, Peter Izsak, Moshe Wasserblat, Danqi Chen
conference: "Arxiv"
year: 2024
bibkey: yen2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02694"}
tags: ['Few-Shot', 'Survey Paper', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications', 'In-Context Learning']
---
Many benchmarks exist for evaluating long-context language models (LCLMs),
yet developers often rely on synthetic tasks such as needle-in-a-haystack
(NIAH) or an arbitrary subset of tasks. However, it remains unclear whether
these benchmarks reflect the diverse downstream applications of LCLMs, and such
inconsistencies further complicate model comparison. We investigate the
underlying reasons behind these practices and find that existing benchmarks
often provide noisy signals due to limited coverage of applications,
insufficient context lengths, unreliable metrics, and incompatibility with base
models. In this work, we introduce HELMET (How to Evaluate Long-context Models
Effectively and Thoroughly), a comprehensive benchmark encompassing seven
diverse, application-centric categories. We also address several issues in
previous benchmarks by adding controllable lengths up to 128K tokens,
model-based evaluation for reliable metrics, and few-shot prompting for
robustly evaluating base models. Consequently, we demonstrate that HELMET
offers more reliable and consistent rankings of frontier LCLMs. Through a
comprehensive study of 59 LCLMs, we find that (1) synthetic tasks like NIAH do
not reliably predict downstream performance; (2) the diverse categories in
HELMET exhibit distinct trends and low correlations with each other; and (3)
while most LCLMs achieve perfect NIAH scores, open-source models significantly
lag behind closed ones when tasks require full-context reasoning or following
complex instructions -- the gap widens as length increases. Finally, we
recommend using our RAG tasks for fast model development, as they are easy to
run and better predict other downstream performance; ultimately, we advocate
for a holistic evaluation across diverse tasks.
