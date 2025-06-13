---
layout: publication
title: 'Memorag: Boosting Long Context Processing With Global Memory-enhanced Retrieval Augmentation'
authors: Hongjin Qian, Zheng Liu, Peitian Zhang, Kelong Mao, Defu Lian, Zhicheng Dou, Tiejun Huang
conference: "Arxiv"
year: 2024
bibkey: qian2024boosting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.05591'}
tags: ['RAG', 'Model Architecture', 'Applications', 'Tools', 'Reinforcement Learning']
---
Processing long contexts presents a significant challenge for large language
models (LLMs). While recent advancements allow LLMs to handle much longer
contexts than before (e.g., 32K or 128K tokens), it is computationally
expensive and can still be insufficient for many applications.
Retrieval-Augmented Generation (RAG) is considered a promising strategy to
address this problem. However, conventional RAG methods face inherent
limitations because of two underlying requirements: 1) explicitly stated
queries, and 2) well-structured knowledge. These conditions, however, do not
hold in general long-context processing tasks.
  In this work, we propose MemoRAG, a novel RAG framework empowered by global
memory-augmented retrieval. MemoRAG features a dual-system architecture. First,
it employs a light but long-range system to create a global memory of the long
context. Once a task is presented, it generates draft answers, providing useful
clues for the retrieval tools to locate relevant information within the long
context. Second, it leverages an expensive but expressive system, which
generates the final answer based on the retrieved information. Building upon
this fundamental framework, we realize the memory module in the form of KV
compression, and reinforce its memorization and cluing capacity from the
Generation quality's Feedback (a.k.a. RLGF). In our experiments, MemoRAG
achieves superior performances across a variety of long-context evaluation
tasks, not only complex scenarios where traditional RAG methods struggle, but
also simpler ones where RAG is typically applied.
