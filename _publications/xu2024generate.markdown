---
layout: publication
title: 'Generate-on-graph: Treat LLM As Both Agent And KG In Incomplete Knowledge Graph Question Answering'
authors: Yao Xu, Shizhu He, Jiabei Chen, Zihao Wang, Yangqiu Song, Hanghang Tong, Guang Liu, Kang Liu, Jun Zhao
conference: "Arxiv"
year: 2024
bibkey: xu2024generate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.14741'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
To address the issues of insufficient knowledge and hallucination in Large
Language Models (LLMs), numerous studies have explored integrating LLMs with
Knowledge Graphs (KGs). However, these methods are typically evaluated on
conventional Knowledge Graph Question Answering (KGQA) with complete KGs, where
all factual triples required for each question are entirely covered by the
given KG. In such cases, LLMs primarily act as an agent to find answer entities
within the KG, rather than effectively integrating the internal knowledge of
LLMs and external knowledge sources such as KGs. In fact, KGs are often
incomplete to cover all the knowledge required to answer questions. To simulate
these real-world scenarios and evaluate the ability of LLMs to integrate
internal and external knowledge, we propose leveraging LLMs for QA under
Incomplete Knowledge Graph (IKGQA), where the provided KG lacks some of the
factual triples for each question, and construct corresponding datasets. To
handle IKGQA, we propose a training-free method called Generate-on-Graph (GoG),
which can generate new factual triples while exploring KGs. Specifically, GoG
performs reasoning through a Thinking-Searching-Generating framework, which
treats LLM as both Agent and KG in IKGQA. Experimental results on two datasets
demonstrate that our GoG outperforms all previous methods.
