---
layout: publication
title: 'Kc-genre: A Knowledge-constrained Generative Re-ranking Method Based On Large Language Models For Knowledge Graph Completion'
authors: Yilin Wang, Minghao Hu, Zhen Huang, Dongsheng Li, Dong Yang, Xicheng Lu
conference: "Arxiv"
year: 2024
bibkey: wang2024kc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17532"}
tags: ['RAG', 'Training Techniques', 'Prompting', 'Applications']
---
The goal of knowledge graph completion (KGC) is to predict missing facts
among entities. Previous methods for KGC re-ranking are mostly built on
non-generative language models to obtain the probability of each candidate.
Recently, generative large language models (LLMs) have shown outstanding
performance on several tasks such as information extraction and dialog systems.
Leveraging them for KGC re-ranking is beneficial for leveraging the extensive
pre-trained knowledge and powerful generative capabilities. However, it may
encounter new problems when accomplishing the task, namely mismatch,
misordering and omission. To this end, we introduce KC-GenRe, a
knowledge-constrained generative re-ranking method based on LLMs for KGC. To
overcome the mismatch issue, we formulate the KGC re-ranking task as a
candidate identifier sorting generation problem implemented by generative LLMs.
To tackle the misordering issue, we develop a knowledge-guided interactive
training method that enhances the identification and ranking of candidates. To
address the omission issue, we design a knowledge-augmented constrained
inference method that enables contextual prompting and controlled generation,
so as to obtain valid rankings. Experimental results show that KG-GenRe
achieves state-of-the-art performance on four datasets, with gains of up to
6.7% and 7.7% in the MRR and Hits@1 metric compared to previous methods, and
9.0% and 11.1% compared to that without re-ranking. Extensive analysis
demonstrates the effectiveness of components in KG-GenRe.
