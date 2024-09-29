---
layout: publication
title: Empowering Large Language Models To Set Up A Knowledge Retrieval Indexer Via Self-learning
authors: Liang Xun, Niu Simin, Li Zhiyu, Zhang Sensen, Song Shichao, Wang Hanyu, Yang Jiawei, Xiong Feiyu, Tang Bo, Xi Chenyang
conference: "Arxiv"
year: 2024
bibkey: liang2024empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16933"}
  - {name: "Code", url: "https://github.com/IAAR-Shanghai/PGRAG"}
tags: ['Has Code', 'RAG', 'Tools']
---
Retrieval-Augmented Generation (RAG) offers a cost-effective approach to injecting real-time knowledge into large language models (LLMs). Nevertheless constructing and validating high-quality knowledge repositories require considerable effort. We propose a pre-retrieval framework named Pseudo-Graph Retrieval-Augmented Generation (PG-RAG) which conceptualizes LLMs as students by providing them with abundant raw reading materials and encouraging them to engage in autonomous reading to record factual information in their own words. The resulting concise well-organized mental indices are interconnected through common topics or complementary facts to form a pseudo-graph database. During the retrieval phase PG-RAG mimics the human behavior in flipping through notes identifying fact paths and subsequently exploring the related contexts. Adhering to the principle of the path taken by many is the best it integrates highly corroborated fact paths to provide a structured and refined sub-graph assisting LLMs. We validated PG-RAG on three specialized question-answering datasets. In single-document tasks PG-RAG significantly outperformed the current best baseline KGP-LLaMA across all key evaluation metrics with an average overall performance improvement of 11.637;. Specifically its BLEU score increased by approximately 14.337; and the QE-F1 metric improved by 23.737;. In multi-document scenarios the average metrics of PG-RAG were at least 2.3537; higher than the best baseline. Notably the BLEU score and QE-F1 metric showed stable improvements of around 7.5537; and 12.7537; respectively. Our code https://github.com/IAAR-Shanghai/PGRAG.
