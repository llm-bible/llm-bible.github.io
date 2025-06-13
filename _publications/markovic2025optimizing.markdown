---
layout: publication
title: 'Optimizing The Interface Between Knowledge Graphs And Llms For Complex Reasoning'
authors: Vasilije Markovic, Lazar Obradovic, Laszlo Hajdu, Jovan Pavlovic
conference: "Arxiv"
year: 2025
bibkey: markovic2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24478"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Prompting']
---
Integrating Large Language Models (LLMs) with Knowledge Graphs (KGs) results in complex systems with numerous hyperparameters that directly affect performance. While such systems are increasingly common in retrieval-augmented generation, the role of systematic hyperparameter optimization remains underexplored. In this paper, we study this problem in the context of Cognee, a modular framework for end-to-end KG construction and retrieval. Using three multi-hop QA benchmarks (HotPotQA, TwoWikiMultiHop, and MuSiQue) we optimize parameters related to chunking, graph construction, retrieval, and prompting. Each configuration is scored using established metrics (exact match, F1, and DeepEval's LLM-based correctness metric). Our results demonstrate that meaningful gains can be achieved through targeted tuning. While the gains are consistent, they are not uniform, with performance varying across datasets and metrics. This variability highlights both the value of tuning and the limitations of standard evaluation measures. While demonstrating the immediate potential of hyperparameter tuning, we argue that future progress will depend not only on architectural advances but also on clearer frameworks for optimization and evaluation in complex, modular systems.
