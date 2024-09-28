---
layout: publication
title: Generate-on-Graph Treat LLM as both Agent and KG in Incomplete Knowledge Graph Question Answering
authors: Xu Yao, He Shizhu, Chen Jiabei, Wang Zihao, Song Yangqiu, Tong Hanghang, Liu Kang, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: xu2024generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14741"}
tags: ['Applications', 'LLM', 'Arxiv']
---
To address the issue of insufficient knowledge and the tendency to generate hallucination in Large Language Models (LLMs) numerous studies have endeavored to integrate LLMs with Knowledge Graphs (KGs). However all these methods are evaluated on conventional Knowledge Graph Question Answering (KGQA) with complete KGs where the factual triples involved in each question are entirely covered by the given KG. In this situation LLM mainly acts as an agent to find answer entities by exploring the KG rather than effectively integrating internal and external knowledge sources. However in real-world scenarios KGs are often incomplete to cover all the knowledge required to answer questions. To simulate real-world scenarios and evaluate the ability of LLMs to integrate internal and external knowledge in this paper we propose leveraging LLMs for QA under Incomplete Knowledge Graph (IKGQA) where the given KG doesnt include all the factual triples involved in each question. To handle IKGQA we propose a training-free method called Generate-on-Graph (GoG) that can generate new factual triples while exploring on KGs. Specifically we propose a selecting-generating-answering framework which not only treat the LLM as an agent to explore on KGs but also treat it as a KG to generate new facts based on the explored subgraph and its inherent knowledge. Experimental results on two datasets demonstrate that our GoG can solve IKGQA to a certain extent while almost all previous methods cannot perform well on IKGQA.
