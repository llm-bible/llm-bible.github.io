---
layout: publication
title: 'Thinkpatterns-21k: A Systematic Study On The Impact Of Thinking Patterns In Llms'
authors: Pengcheng Wen, Jiaming Ji, Chi-min Chan, Juntao Dai, Donghai Hong, Yaodong Yang, Sirui Han, Yike Guo
conference: "Arxiv"
year: 2025
bibkey: wen2025thinkpatterns
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.12918'}
tags: ['Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have demonstrated enhanced performance through
the \textit\{Thinking then Responding\} paradigm, where models generate internal
thoughts before final responses (aka, System 2 thinking). However, existing
research lacks a systematic understanding of the mechanisms underlying how
thinking patterns affect performance across model sizes. In this work, we
conduct a comprehensive analysis of the impact of various thinking types on
model performance and introduce ThinkPatterns-21k, a curated dataset comprising
21k instruction-response pairs (QA) collected from existing
instruction-following datasets with five thinking types. For each pair, we
augment it with five distinct internal thinking patterns: one unstructured
thinking (monologue) and four structured variants (decomposition, self-ask,
self-debate and self-critic), while maintaining the same instruction and
response. Through extensive evaluation across different model sizes (3B-32B
parameters), we have two key findings: (1) smaller models (<30B parameters) can
benefit from most of structured thinking patterns, while larger models (32B)
with structured thinking like decomposition would degrade performance and (2)
unstructured monologue demonstrates broad effectiveness across different model
sizes. Finally, we released all of our datasets, checkpoints, training logs of
diverse thinking patterns to reproducibility, aiming to facilitate further
research in this direction.
