---
layout: publication
title: 'Automated Text-to-table For Reasoning-intensive Table QA: Pipeline Design And Benchmarking Insights'
authors: Shi-yu Tian, Zhi Zhou, Wei Dong, Ming Yang, Kun-yang Yu, Zi-jian Cheng, Lan-zhe Guo, Yu-feng Li
conference: "Arxiv"
year: 2025
bibkey: tian2025automated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19563'}
tags: ['Reinforcement Learning', 'Security', 'Applications']
---
Reasoning with tabular data holds increasing importance in modern applications, yet comprehensive evaluation methodologies for reasoning-intensive Table Question Answering (QA) tasks remain nascent. Existing research is constrained by two primary bottlenecks: 1) Reliance on costly manually annotated real-world data, which is difficult to cover complex reasoning scenarios; 2) The heterogeneity of table structures hinders systematic analysis of the intrinsic mechanisms behind the underperformance of LLMs, especially in reasoning-intensive tasks. To address these issues, we propose an automated generation pipeline AutoT2T that transforms mathematical word problems into table-based reasoning tasks, eliminating the need for manual annotation. The pipeline can generate multiple variants of a table for the same reasoning problem, including noisy versions to support robustness evaluation. Based on this, we construct a new benchmark TabularGSM, which systematically spans a range of table complexities and trap problems. Experimental analyses through AutoT2T and TabularGSM reveal that the tight coupling between reasoning and retrieval or identification processes is a key factor underlying the failure of LLMs in complex Table QA tasks. This highlights the necessity for models to develop synergistic reasoning capabilities in order to perform effectively in complex Table QA tasks.
