---
layout: publication
title: 'SHED: Shapley-based Automated Dataset Refinement For Instruction Fine-tuning'
authors: Yexiao He, Ziyao Wang, Zheyu Shen, Guoheng Sun, Yucong Dai, Yongkai Wu, Hongyi Wang, Ang Li
conference: "Arxiv"
year: 2024
bibkey: he2024shapley
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.00705'}
tags: ['Training Techniques', 'Fine-Tuning', 'Tools', 'Pretraining Methods']
---
The pre-trained Large Language Models (LLMs) can be adapted for many
downstream tasks and tailored to align with human preferences through
fine-tuning. Recent studies have discovered that LLMs can achieve desirable
performance with only a small amount of high-quality data, suggesting that a
large amount of the data in these extensive datasets is redundant or even
harmful. Identifying high-quality data from vast datasets to curate small yet
effective datasets has emerged as a critical challenge. In this paper, we
introduce SHED, an automated dataset refinement framework based on Shapley
value for instruction fine-tuning. SHED eliminates the need for human
intervention or the use of commercial LLMs. Moreover, the datasets curated
through SHED exhibit transferability, indicating they can be reused across
different LLMs with consistently high performance. We conduct extensive
experiments to evaluate the datasets curated by SHED. The results demonstrate
SHED's superiority over state-of-the-art methods across various tasks and LLMs;
notably, datasets comprising only 10% of the original data selected by SHED
achieve performance comparable to or surpassing that of the full datasets.
