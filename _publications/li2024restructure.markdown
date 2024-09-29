---
layout: publication
title: Refiner Restructure Retrieval Content Efficiently To Advance Question45;answering Capabilities
authors: Li Zhonghao, Hu Xuming, Liu Aiwei, Zheng Kening, Huang Sirui, Xiong Hui
conference: "Arxiv"
year: 2024
bibkey: li2024restructure
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11357"}
tags: ['Applications', 'RAG', 'Tools']
---
Large Language Models (LLMs) are limited by their parametric knowledge leading to hallucinations in knowledge45;extensive tasks. To address this Retrieval45;Augmented Generation (RAG) incorporates external document chunks to expand LLM knowledge. Furthermore compressing information from document chunks through extraction or summarization can improve LLM performance. Nonetheless LLMs still struggle to notice and utilize scattered key information a problem known as the lost45;in45;the45;middle syndrome. Therefore we typically need to restructure the content for LLM to recognize the key information. We propose textit123;Refiner125; an end45;to45;end extract45;and45;restructure paradigm that operates in the post45;retrieval process of RAG. textit123;Refiner125; leverages a single decoder45;only LLM to adaptively extract query45;relevant contents verbatim along with the necessary context and section them based on their interconnectedness thereby highlights information distinction and aligns downstream LLMs with the original context effectively. Experiments show that a trained textit123;Refiner125; (with 7B parameters) exhibits significant gain to downstream LLM in improving answer accuracy and outperforms other state45;of45;the45;art advanced RAG and concurrent compressing approaches in various single45;hop and multi45;hop QA tasks. Notably textit123;Refiner125; achieves a 80.537; tokens reduction and a 1.645;7.037; improvement margin in multi45;hop tasks compared to the next best solution. textit123;Refiner125; is a plug45;and45;play solution that can be seamlessly integrated with RAG systems facilitating its application across diverse open45;source frameworks.
