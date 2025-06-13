---
layout: publication
title: 'Medagentsbench: Benchmarking Thinking Models And Agent Frameworks For Complex Medical Reasoning'
authors: Xiangru Tang, Daniel Shao, Jiwoong Sohn, Jiapeng Chen, Jiayi Zhang, Jinyu Xiang, Fang Wu, Yilun Zhao, Chenglin Wu, Wenqi Shi, Arman Cohan, Mark Gerstein
conference: "Arxiv"
year: 2025
bibkey: tang2025benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07459"}
  - {name: "Code", url: "https://github.com/gersteinlab/medagents-benchmark"}
tags: ['Agentic', 'Has Code', 'Tools']
---
Large Language Models (LLMs) have shown impressive performance on existing
medical question-answering benchmarks. This high performance makes it
increasingly difficult to meaningfully evaluate and differentiate advanced
methods. We present MedAgentsBench, a benchmark that focuses on challenging
medical questions requiring multi-step clinical reasoning, diagnosis
formulation, and treatment planning-scenarios where current models still
struggle despite their strong performance on standard tests. Drawing from seven
established medical datasets, our benchmark addresses three key limitations in
existing evaluations: (1) the prevalence of straightforward questions where
even base models achieve high performance, (2) inconsistent sampling and
evaluation protocols across studies, and (3) lack of systematic analysis of the
interplay between performance, cost, and inference time. Through experiments
with various base models and reasoning methods, we demonstrate that the latest
thinking models, DeepSeek R1 and OpenAI o3, exhibit exceptional performance in
complex medical reasoning tasks. Additionally, advanced search-based agent
methods offer promising performance-to-cost ratios compared to traditional
approaches. Our analysis reveals substantial performance gaps between model
families on complex questions and identifies optimal model selections for
different computational constraints. Our benchmark and evaluation framework are
publicly available at https://github.com/gersteinlab/medagents-benchmark.
