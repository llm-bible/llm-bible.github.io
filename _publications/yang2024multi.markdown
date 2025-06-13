---
layout: publication
title: 'Execrepobench: Multi-level Executable Code Completion Evaluation'
authors: Jian Yang, Jiajun Zhang, Jiaxi Yang, Ke Jin, Lei Zhang, Qiyao Peng, Ken Deng, Yibo Miao, Tianyu Liu, Zeyu Cui, Binyuan Hui, Junyang Lin
conference: "Arxiv"
year: 2024
bibkey: yang2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11990"}
  - {name: "Code", url: "https://execrepobench.github.io/"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Code completion has become an essential tool for daily software development.
Existing evaluation benchmarks often employ static methods that do not fully
capture the dynamic nature of real-world coding environments and face
significant challenges, including limited context length, reliance on
superficial evaluation metrics, and potential overfitting to training datasets.
In this work, we introduce a novel framework for enhancing code completion in
software development through the creation of a repository-level benchmark
ExecRepoBench and the instruction corpora Repo-Instruct, aim at improving the
functionality of open-source large language models (LLMs) in real-world coding
scenarios that involve complex interdependencies across multiple files.
ExecRepoBench includes 1.2K samples from active Python repositories. Plus, we
present a multi-level grammar-based completion methodology conditioned on the
abstract syntax tree to mask code fragments at various logical units (e.g.
statements, expressions, and functions). Then, we fine-tune the open-source LLM
with 7B parameters on Repo-Instruct to produce a strong code completion
baseline model Qwen2.5-Coder-Instruct-C based on the open-source model.
Qwen2.5-Coder-Instruct-C is rigorously evaluated against existing benchmarks,
including MultiPL-E and ExecRepoBench, which consistently outperforms prior
baselines across all programming languages. The deployment of \ourmethod\{\} can
be used as a high-performance, local service for programming
development\footnote\{\url\{https://execrepobench.github.io/\}\}.
