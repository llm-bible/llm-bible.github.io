---
layout: publication
title: TRACE The Evidence Constructing Knowledge45;grounded Reasoning Chains For Retrieval45;augmented Generation
authors: Fang Jinyuan, Meng Zaiqiao, Macdonald Craig
conference: "Arxiv"
year: 2024
bibkey: fang2024trace
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11460"}
tags: ['Applications', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Retrieval45;augmented generation (RAG) offers an effective approach for addressing question answering (QA) tasks. However the imperfections of the retrievers in RAG models often result in the retrieval of irrelevant information which could introduce noises and degrade the performance especially when handling multi45;hop questions that require multiple steps of reasoning. To enhance the multi45;hop reasoning ability of RAG models we propose TRACE. TRACE constructs knowledge45;grounded reasoning chains which are a series of logically connected knowledge triples to identify and integrate supporting evidence from the retrieved documents for answering questions. Specifically TRACE employs a KG Generator to create a knowledge graph (KG) from the retrieved documents and then uses an Autoregressive Reasoning Chain Constructor to build reasoning chains. Experimental results on three multi45;hop QA datasets show that TRACE achieves an average performance improvement of up to 14.0337; compared to using all the retrieved documents. Moreover the results indicate that using reasoning chains as context rather than the entire documents is often sufficient to correctly answer questions.
