---
layout: publication
title: 'Rageval: Scenario Specific RAG Evaluation Dataset Generation Framework'
authors: Zhu Kunlun, Luo Yifan, Xu Dingling, Wang Ruobing, Yu Shi, Wang Shuo, Yan Yukun, Liu Zhenghao, Han Xu, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2024
bibkey: zhu2024scenario
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01262"}
tags: ['Merging', 'RAG', 'Tools']
---
Retrieval-Augmented Generation (RAG) systems have demonstrated their
advantages in alleviating the hallucination of Large Language Models (LLMs).
Existing RAG benchmarks mainly focus on evaluating whether LLMs can correctly
answer the general knowledge. However, they are unable to evaluate the
effectiveness of the RAG system in dealing with the data from different
vertical domains. This paper introduces RAGEval, a framework for automatically
generating evaluation datasets to evaluate the knowledge usage ability of
different LLMs in different scenarios. Specifically, RAGEval summarizes a
schema from seed documents, applies the configurations to generate diverse
documents, and constructs question-answering pairs according to both articles
and configurations. We propose three novel metrics, Completeness,
Hallucination, and Irrelevance, to carefully evaluate the responses generated
by LLMs. By benchmarking RAG models in vertical domains, RAGEval has the
ability to better evaluate the knowledge usage ability of LLMs, which avoids
the confusion regarding the source of knowledge in answering question in
existing QA datasets--whether it comes from parameterized memory or retrieval.
The code and dataset will be released.
