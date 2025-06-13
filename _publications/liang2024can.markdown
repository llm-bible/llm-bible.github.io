---
layout: publication
title: 'Can Language Models Replace Programmers? REPOCOD Says ''not Yet'''
authors: Shanchao Liang, Yiran Hu, Nan Jiang, Lin Tan
conference: "Arxiv"
year: 2024
bibkey: liang2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21647'}
  - {name: "Code", url: 'https://github.com/lt-asset/REPOCOD'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code', 'Applications']
---
Large language models (LLMs) have achieved high accuracy, i.e., more than 90%
pass@1, in solving Python coding problems in HumanEval and MBPP. Thus, a
natural question is, whether LLMs achieve comparable code completion
performance compared to human developers? Unfortunately, one cannot answer this
question using existing manual crafted or simple (e.g., single-line) code
generation benchmarks, since such tasks fail to represent real-world software
development tasks. In addition, existing benchmarks often use poor code
correctness metrics, providing misleading conclusions.
  To address these challenges, we create REPOCOD, a code generation benchmark
with 980 problems collected from 11 popular real-world projects, with more than
58% of them requiring file-level or repository-level context information. In
addition, REPOCOD has the longest average canonical solution length (331.6
tokens) and the highest average cyclomatic complexity (9.00) compared to
existing benchmarks. Each task in REPOCOD includes 313.5 developer-written test
cases on average for better correctness evaluation. In our evaluations of ten
LLMs, none of the models achieve more than 30% pass@1 on REPOCOD, indicating
the necessity of building stronger LLMs that can help developers in real-world
software development. REPOCOD is available at
https://github.com/lt-asset/REPOCOD
