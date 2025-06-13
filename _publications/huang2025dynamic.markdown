---
layout: publication
title: 'Thinkbench: Dynamic Out-of-distribution Evaluation For Robust LLM Reasoning'
authors: Shulin Huang, Linyi Yang, Yan Song, Shuang Chen, Leyang Cui, Ziyu Wan, Qingcheng Zeng, Ying Wen, Kun Shao, Weinan Zhang, Jun Wang, Yue Zhang
conference: "Arxiv"
year: 2025
bibkey: huang2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16268"}
tags: ['Tools', 'Reinforcement Learning']
---
Evaluating large language models (LLMs) poses significant challenges,
particularly due to issues of data contamination and the leakage of correct
answers. To address these challenges, we introduce ThinkBench, a novel
evaluation framework designed to evaluate LLMs' reasoning capability robustly.
ThinkBench proposes a dynamic data generation method for constructing
out-of-distribution (OOD) datasets and offers an OOD dataset that contains
2,912 samples drawn from reasoning tasks. ThinkBench unifies the evaluation of
reasoning models and non-reasoning models. We evaluate 16 LLMs and 4 PRMs under
identical experimental conditions and show that most of the LLMs' performance
are far from robust and they face a certain level of data leakage. By
dynamically generating OOD datasets, ThinkBench effectively provides a reliable
evaluation of LLMs and reduces the impact of data contamination.
