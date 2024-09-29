---
layout: publication
title: Refiner Restructure Retrieval Content Efficiently to Advance Question-Answering Capabilities
authors: Li Zhonghao, Hu Xuming, Liu Aiwei, Zheng Kening, Huang Sirui, Xiong Hui
conference: "Arxiv"
year: 2024
bibkey: li2024refiner
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11357"}
tags: ['Applications', 'RAG', 'Tools']
---
Large Language Models (LLMs) are limited by their parametric knowledge leading to hallucinations in knowledge-extensive tasks. To address this Retrieval-Augmented Generation (RAG) incorporates external document chunks to expand LLM knowledge. Furthermore compressing information from document chunks through extraction or summarization can improve LLM performance. Nonetheless LLMs still struggle to notice and utilize scattered key information a problem known as the lost-in-the-middle syndrome. Therefore we typically need to restructure the content for LLM to recognize the key information. We propose textitRefiner an end-to-end extract-and-restructure paradigm that operates in the post-retrieval process of RAG. textitRefiner leverages a single decoder-only LLM to adaptively extract query-relevant contents verbatim along with the necessary context and section them based on their interconnectedness thereby highlights information distinction and aligns downstream LLMs with the original context effectively. Experiments show that a trained textitRefiner (with 7B parameters) exhibits significant gain to downstream LLM in improving answer accuracy and outperforms other state-of-the-art advanced RAG and concurrent compressing approaches in various single-hop and multi-hop QA tasks. Notably textitRefiner achieves a 80.5 tokens reduction and a 1.6-7.0 improvement margin in multi-hop tasks compared to the next best solution. textitRefiner is a plug-and-play solution that can be seamlessly integrated with RAG systems facilitating its application across diverse open-source frameworks.
