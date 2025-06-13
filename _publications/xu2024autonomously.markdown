---
layout: publication
title: 'Activerag: Autonomously Knowledge Assimilation And Accommodation Through Retrieval-augmented Agents'
authors: Zhipeng Xu, Zhenghao Liu, Yukun Yan, Shuo Wang, Shi Yu, Zheni Zeng, Chaojun Xiao, Zhiyuan Liu, Ge Yu, Chenyan Xiong
conference: "Arxiv"
year: 2024
bibkey: xu2024autonomously
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13547"}
  - {name: "Code", url: "https://github.com/OpenMatch/ActiveRAG"}
tags: ['RAG', 'Agentic', 'Has Code', 'Tools']
---
Retrieval-Augmented Generation (RAG) enables Large Language Models (LLMs) to
leverage external knowledge, enhancing their performance on knowledge-intensive
tasks. However, existing RAG models often treat LLMs as passive recipients of
information, which can lead to interference from noisy retrieved content. In
this paper, we introduce ActiveRAG, a multi-agent framework that mimics human
learning behavior to help LLMs actively engage with and learn from retrieved
evidence. ActiveRAG designs a knowledge assimilation agent to form the
knowledge understanding by associating external knowledge with the parametric
memory of LLMs. Then our model employs the thought accommodation agent to
calibrate the internal thought of LLMs for response refinement. Our experiments
show that ActiveRAG achieves a 10% improvement over vanilla RAG on various
question-answering benchmarks. Further analysis reveals that ActiveRAG
mitigates the impact of noisy retrievals, alleviates conflicts between external
knowledge and parametric memory and improves the self-consistency of LLMs in
answering the question. All data and codes are available at
https://github.com/OpenMatch/ActiveRAG.
