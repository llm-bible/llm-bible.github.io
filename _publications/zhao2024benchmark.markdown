---
layout: publication
title: 'Bento: Benchmark Task Reduction With In-context Transferability'
authors: Hongyu Zhao, Ming Li, Lichao Sun, Tianyi Zhou
conference: "Arxiv"
year: 2024
bibkey: zhao2024benchmark
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13804'}
tags: ['Prompting', 'In-Context Learning', 'Training Techniques']
---
Evaluating large language models (LLMs) is costly: it requires the generation
and examination of LLM outputs on a large-scale benchmark of various tasks.
This paper investigates how to efficiently reduce the tasks used to benchmark
LLMs without affecting the evaluation quality. Our study reveals that task
transferability and relevance provide critical information to identify the most
representative subset of tasks via optimizing a facility location function. We
propose a practically efficient metric for estimating the transferability
between two tasks via in-context learning (ICL). By analyzing the pairwise
transferability, we can reduce tasks in a modern LLM benchmark (e.g., MMLU or
FLAN) to 5% while inducing only a <4% difference to the evaluation on the
original benchmark. Compared to prior works, our method is training-free,
gradient-free, and highly efficient requiring ICL only.
