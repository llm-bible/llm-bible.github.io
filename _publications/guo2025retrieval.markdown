---
layout: publication
title: 'Retrieval-augmented Generation As Noisy In-context Learning: A Unified Theory And Risk Bounds'
authors: Yang Guo, Yutian Tao, Yifei Ming, Robert D. Nowak, Yingyu Liang
conference: "Arxiv"
year: 2025
bibkey: guo2025retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03100"}
tags: ['Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Retrieval-augmented generation (RAG) has seen many empirical successes in recent years by aiding the LLM with external knowledge. However, its theoretical aspect has remained mostly unexplored. In this paper, we propose the first finite-sample generalization bound for RAG in in-context linear regression and derive an exact bias-variance tradeoff. Our framework views the retrieved texts as query-dependent noisy in-context examples and recovers the classical in-context learning (ICL) and standard RAG as the limit cases. Our analysis suggests that an intrinsic ceiling on generalization error exists on RAG as opposed to the ICL. Furthermore, our framework is able to model retrieval both from the training data and from external corpora by introducing uniform and non-uniform RAG noise. In line with our theory, we show the sample efficiency of ICL and RAG empirically with experiments on common QA benchmarks, such as Natural Questions and TriviaQA.
