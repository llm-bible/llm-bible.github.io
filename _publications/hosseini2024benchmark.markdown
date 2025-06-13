---
layout: publication
title: 'A Benchmark For Long-form Medical Question Answering'
authors: Pedram Hosseini, Jessica M. Sin, Bing Ren, Bryceton G. Thomas, Elnaz Nouri, Ali Farahanchi, Saeed Hassanpour
conference: "Arxiv"
year: 2024
bibkey: hosseini2024benchmark
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.09834'}
  - {name: "Code", url: 'https://github.com/lavita-ai/medical-eval-sphere'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Has Code', 'Applications']
---
There is a lack of benchmarks for evaluating large language models (LLMs) in
long-form medical question answering (QA). Most existing medical QA evaluation
benchmarks focus on automatic metrics and multiple-choice questions. While
valuable, these benchmarks fail to fully capture or assess the complexities of
real-world clinical applications where LLMs are being deployed. Furthermore,
existing studies on evaluating long-form answer generation in medical QA are
primarily closed-source, lacking access to human medical expert annotations,
which makes it difficult to reproduce results and enhance existing baselines.
In this work, we introduce a new publicly available benchmark featuring
real-world consumer medical questions with long-form answer evaluations
annotated by medical doctors. We performed pairwise comparisons of responses
from various open and closed-source medical and general-purpose LLMs based on
criteria such as correctness, helpfulness, harmfulness, and bias. Additionally,
we performed a comprehensive LLM-as-a-judge analysis to study the alignment
between human judgments and LLMs. Our preliminary results highlight the strong
potential of open LLMs in medical QA compared to leading closed models. Code &
Data: https://github.com/lavita-ai/medical-eval-sphere
