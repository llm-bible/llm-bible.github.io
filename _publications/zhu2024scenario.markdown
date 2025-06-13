---
layout: publication
title: 'Rageval: Scenario Specific RAG Evaluation Dataset Generation Framework'
authors: Kunlun Zhu, Yifan Luo, Dingling Xu, Yukun Yan, Zhenghao Liu, Shi Yu, Ruobing Wang, Shuo Wang, Yishan Li, Nan Zhang, Xu Han, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: zhu2024scenario
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01262"}
  - {name: "Code", url: "https://github.com/OpenBMB/RAGEval"}
tags: ['Responsible AI', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Has Code']
---
Retrieval-Augmented Generation (RAG) is a powerful approach that enables
large language models (LLMs) to incorporate external knowledge. However,
evaluating the effectiveness of RAG systems in specialized scenarios remains
challenging due to the high costs of data construction and the lack of suitable
evaluation metrics. This paper introduces RAGEval, a framework designed to
assess RAG systems across diverse scenarios by generating high-quality
documents, questions, answers, and references through a schema-based pipeline.
With a focus on factual accuracy, we propose three novel metrics: Completeness,
Hallucination, and Irrelevance to evaluate LLM generated responses rigorously.
Experimental results show that RAGEval outperforms zero-shot and one-shot
methods in terms of clarity, safety, conformity, and richness of generated
samples. Furthermore, the use of LLMs for scoring the proposed metrics
demonstrates a high level of consistency with human evaluations. RAGEval
establishes a new paradigm for evaluating RAG systems in real-world
applications. The code and dataset are released at
https://github.com/OpenBMB/RAGEval.
