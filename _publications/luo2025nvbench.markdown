---
layout: publication
title: 'Nvbench 2.0: A Benchmark For Natural Language To Visualization Under Ambiguity'
authors: Tianqi Luo, Chuhan Huang, Leixian Shen, Boyan Li, Shuyu Shen, Wei Zeng, Nan Tang, Yuyu Luo
conference: "Arxiv"
year: 2025
bibkey: luo2025nvbench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12880"}
tags: ['Efficiency and Optimization']
---
Natural Language to Visualization (NL2VIS) enables users to create
visualizations from natural language queries, making data insights more
accessible. However, NL2VIS faces challenges in interpreting ambiguous queries,
as users often express their visualization needs in imprecise language. To
address this challenge, we introduce nvBench 2.0, a new benchmark designed to
evaluate NL2VIS systems in scenarios involving ambiguous queries. nvBench 2.0
includes 7,878 natural language queries and 24,076 corresponding
visualizations, derived from 780 tables across 153 domains. It is built using a
controlled ambiguity-injection pipeline that generates ambiguous queries
through a reverse-generation workflow. By starting with unambiguous seed
visualizations and selectively injecting ambiguities, the pipeline yields
multiple valid interpretations for each query, with each ambiguous query
traceable to its corresponding visualization through step-wise reasoning paths.
We evaluate various Large Language Models (LLMs) on their ability to perform
ambiguous NL2VIS tasks using nvBench 2.0. We also propose Step-NL2VIS, an
LLM-based model trained on nvBench 2.0, which enhances performance in ambiguous
scenarios through step-wise preference optimization. Our results show that
Step-NL2VIS outperforms all baselines, setting a new state-of-the-art for
ambiguous NL2VIS tasks.
