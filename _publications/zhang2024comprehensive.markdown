---
layout: publication
title: 'Pediabench: A Comprehensive Chinese Pediatric Dataset For Benchmarking Large Language Models'
authors: Qian Zhang, Panfeng Chen, Jiali Li, Linkun Feng, Shuyu Liu, Heng Zhao, Mei Chen, Hui Li, Yanhao Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06287'}
  - {name: "Code", url: 'https://github.com/ACMISLab/PediaBench'}
tags: ['Has Code', 'Uncategorized']
---
The emergence of Large Language Models (LLMs) in the medical domain has
stressed a compelling need for standard datasets to evaluate their
question-answering (QA) performance. Although there have been several benchmark
datasets for medical QA, they either cover common knowledge across different
departments or are specific to another department rather than pediatrics.
Moreover, some of them are limited to objective questions and do not measure
the generation capacity of LLMs. Therefore, they cannot comprehensively assess
the QA ability of LLMs in pediatrics. To fill this gap, we construct
PediaBench, the first Chinese pediatric dataset for LLM evaluation.
Specifically, it contains 4,117 objective questions and 1,632 subjective
questions spanning 12 pediatric disease groups. It adopts an integrated scoring
criterion based on different difficulty levels to thoroughly assess the
proficiency of an LLM in instruction following, knowledge understanding,
clinical case analysis, etc. Finally, we validate the effectiveness of
PediaBench with extensive experiments on 20 open-source and commercial LLMs.
Through an in-depth analysis of experimental results, we offer insights into
the ability of LLMs to answer pediatric questions in the Chinese context,
highlighting their limitations for further improvements. Our code and data are
published at https://github.com/ACMISLab/PediaBench.
