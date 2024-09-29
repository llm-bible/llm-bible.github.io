---
layout: publication
title: RAG Foundry A Framework For Enhancing Llms For Retrieval Augmented Generation
authors: Fleischer Daniel, Berchansky Moshe, Wasserblat Moshe, Izsak Peter
conference: "Arxiv"
year: 2024
bibkey: fleischer2024rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02545"}
  - {name: "Code", url: "https://github.com/IntelLabs/RAGFoundry"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Implementing Retrieval-Augmented Generation (RAG) systems is inherently complex requiring deep understanding of data use cases and intricate design decisions. Additionally evaluating these systems presents significant challenges necessitating assessment of both retrieval accuracy and generative quality through a multi-faceted approach. We introduce RAG Foundry an open-source framework for augmenting large language models for RAG use cases. RAG Foundry integrates data creation training inference and evaluation into a single workflow facilitating the creation of data-augmented datasets for training and evaluating large language models in RAG settings. This integration enables rapid prototyping and experimentation with various RAG techniques allowing users to easily generate datasets and train RAG models using internal or specialized knowledge sources. We demonstrate the framework effectiveness by augmenting and fine-tuning Llama-3 and Phi-3 models with diverse RAG configurations showcasing consistent improvements across three knowledge-intensive datasets. Code is released as open-source in https://github.com/IntelLabs/RAGFoundry.
