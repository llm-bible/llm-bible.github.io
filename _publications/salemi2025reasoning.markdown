---
layout: publication
title: 'Reasoning-enhanced Self-training For Long-form Personalized Text Generation'
authors: Alireza Salemi, Cheng Li, Mingyang Zhang, Qiaozhu Mei, Weize Kong, Tao Chen, Zhuowan Li, Michael Bendersky, Hamed Zamani
conference: "Arxiv"
year: 2025
bibkey: salemi2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04167"}
tags: ['Tools', 'Applications', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques']
---
Personalized text generation requires a unique ability of large language
models (LLMs) to learn from context that they often do not encounter during
their standard training. One way to encourage LLMs to better use personalized
context for generating outputs that better align with the user's expectations
is to instruct them to reason over the user's past preferences, background
knowledge, or writing style. To achieve this, we propose Reasoning-Enhanced
Self-Training for Personalized Text Generation (REST-PG), a framework that
trains LLMs to reason over personal data during response generation. REST-PG
first generates reasoning paths to train the LLM's reasoning abilities and then
employs Expectation-Maximization Reinforced Self-Training to iteratively train
the LLM based on its own high-reward outputs. We evaluate REST-PG on the
LongLaMP benchmark, consisting of four diverse personalized long-form text
generation tasks. Our experiments demonstrate that REST-PG achieves significant
improvements over state-of-the-art baselines, with an average relative
performance gain of 14.5% on the benchmark.
