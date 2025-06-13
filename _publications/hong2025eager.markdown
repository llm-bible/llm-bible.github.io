---
layout: publication
title: 'EAGER-LLM: Enhancing Large Language Models As Recommenders Through Exogenous Behavior-semantic Integration'
authors: Minjie Hong, Yan Xia, Zehan Wang, Jieming Zhu, Ye Wang, Sihang Cai, Xiaoda Yang, Quanyu Dai, Zhenhua Dong, Zhimeng Zhang, Zhou Zhao
conference: "Arxiv"
year: 2025
bibkey: hong2025eager
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14735"}
tags: ['RecSys', 'RAG', 'Tools']
---
Large language models (LLMs) are increasingly leveraged as foundational
backbones in the development of advanced recommender systems, offering enhanced
capabilities through their extensive knowledge and reasoning. Existing
llm-based recommender systems (RSs) often face challenges due to the
significant differences between the linguistic semantics of pre-trained LLMs
and the collaborative semantics essential for RSs. These systems use
pre-trained linguistic semantics but learn collaborative semantics from scratch
via the llm-Backbone. However, LLMs are not designed for recommendations,
leading to inefficient collaborative learning, weak result correlations, and
poor integration of traditional RS features. To address these challenges, we
propose EAGER-LLM, a decoder-only llm-based generative recommendation framework
that integrates endogenous and exogenous behavioral and semantic information in
a non-intrusive manner. Specifically, we propose 1)dual-source knowledge-rich
item indices that integrates indexing sequences for exogenous signals, enabling
efficient link-wide processing; 2)non-invasive multiscale alignment
reconstruction tasks guide the model toward a deeper understanding of both
collaborative and semantic signals; 3)an annealing adapter designed to finely
balance the model's recommendation performance with its comprehension
capabilities. We demonstrate EAGER-LLM's effectiveness through rigorous testing
on three public benchmarks.
