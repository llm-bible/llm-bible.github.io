---
layout: publication
title: 'Are Llms Prescient? A Continuous Evaluation Using Daily News As The Oracle'
authors: Hui Dai, Ryan Teehan, Mengye Ren
conference: "Arxiv"
year: 2024
bibkey: dai2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.08324"}
tags: ['RAG', 'Training Techniques', 'Pre-Training', 'ACL']
---
Many existing evaluation benchmarks for Large Language Models (LLMs) quickly
become outdated due to the emergence of new models and training data. These
benchmarks also fall short in assessing how LLM performance changes over time,
as they consist of static questions without a temporal dimension. To address
these limitations, we propose using future event prediction as a continuous
evaluation method to assess LLMs' temporal generalization and forecasting
abilities. Our benchmark, Daily Oracle, automatically generates question-answer
(QA) pairs from daily news, challenging LLMs to predict "future" event
outcomes. Our findings reveal that as pre-training data becomes outdated, LLM
performance degrades over time. While Retrieval Augmented Generation (RAG) has
the potential to enhance prediction accuracy, the performance degradation
pattern persists, highlighting the need for continuous model updates.
