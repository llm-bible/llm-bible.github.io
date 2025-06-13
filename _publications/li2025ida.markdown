---
layout: publication
title: 'Ida-bench: Evaluating Llms On Interactive Guided Data Analysis'
authors: Hanyu Li, Haoyu Liu, Tingyu Zhu, Tianyu Guo, Zeyu Zheng, Xiaotie Deng, Michael I. Jordan
conference: "Arxiv"
year: 2025
bibkey: li2025ida
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18223"}
tags: ['Agentic', 'Reinforcement Learning']
---
Large Language Models (LLMs) show promise as data analysis agents, but existing benchmarks overlook the iterative nature of the field, where experts' decisions evolve with deeper insights of the dataset. To address this, we introduce IDA-Bench, a novel benchmark evaluating LLM agents in multi-round interactive scenarios. Derived from complex Kaggle notebooks, tasks are presented as sequential natural language instructions by an LLM-simulated user. Agent performance is judged by comparing its final numerical output to the human-derived baseline. Initial results show that even state-of-the-art coding agents (like Claude-3.7-thinking) succeed on < 50% of the tasks, highlighting limitations not evident in single-turn tests. This work underscores the need to improve LLMs' multi-round capabilities for building more reliable data analysis agents, highlighting the necessity of achieving a balance between instruction following and reasoning.
