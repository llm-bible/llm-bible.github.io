---
layout: publication
title: 'Top General Performance = Top Domain Performance? Domaincodebench: A Multi-domain Code Generation Benchmark'
authors: Dewu Zheng, Yanlin Wang, Ensheng Shi, Xilin Liu, Yuchi Ma, Hongyu Zhang, Zibin Zheng
conference: "Arxiv"
year: 2024
bibkey: zheng2024top
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18573"}
  - {name: "Code", url: "https://github.com/DeepSoftwareAnalytics/DomainCodeBench"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Applications']
---
With the rapid advancement of large language models (LLMs), extensive
research has been conducted to investigate the code generation capabilities of
LLMs. However, existing efforts primarily focus on general-domain tasks,
leaving LLMs' code generation performance in real-world application domains
underexplored. This raises a critical question: can a model's general-domain
coding ability reliably represent its ability in specialized domains? In this
paper, we introduce DomainCodeBench, a multi-domain code generation benchmark
designed to systematically evaluate LLMs across 12 software application domains
and 15 programming languages. DomainCodeBench contains 2,400 manually verified
tasks with ground truth, human-annotated docstrings, and fine-grained
dependency information to ensure more coverage of domain-specific challenges.
Specifically, we first identify the most popular application domains by topic
mining. Then, we curate coding tasks based on commonly used frameworks and
platforms in each domain. We obtain several findings through extensive
experiments on DomainCodeBench with ten mainstream LLMs. (1) Performance
decoupling: experiments reveal that top general-domain models do not
consistently excel in specific application domains; (2) Domain-specific
weaknesses: LLMs often fail due to domain knowledge gaps and third-party
library misusage; (3) Contextual enhancement: we show that augmenting prompts
with domain-specific knowledge improves performance by around 38.17%, providing
actionable insights for performance optimization. Our replication package,
including the benchmark, source code, and experimental results, is available at
https://github.com/DeepSoftwareAnalytics/DomainCodeBench.
