---
layout: publication
title: 'Improving Zero-shot LLM Re-ranker With Risk Minimization'
authors: Xiaowei Yuan, Zhao Yang, Yequan Wang, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2024
bibkey: yuan2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13331"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Prompting']
---
In the Retrieval-Augmented Generation (RAG) system, advanced Large Language
Models (LLMs) have emerged as effective Query Likelihood Models (QLMs) in an
unsupervised way, which re-rank documents based on the probability of
generating the query given the content of a document. However, directly
prompting LLMs to approximate QLMs inherently is biased, where the estimated
distribution might diverge from the actual document-specific distribution. In
this study, we introduce a novel framework, \\(\mathrm\{UR^3\}\\), which leverages
Bayesian decision theory to both quantify and mitigate this estimation bias.
Specifically, \\(\mathrm\{UR^3\}\\) reformulates the problem as maximizing the
probability of document generation, thereby harmonizing the optimization of
query and document generation probabilities under a unified risk minimization
objective. Our empirical results indicate that \\(\mathrm\{UR^3\}\\) significantly
enhances re-ranking, particularly in improving the Top-1 accuracy. It benefits
the QA tasks by achieving higher accuracy with fewer input documents.
