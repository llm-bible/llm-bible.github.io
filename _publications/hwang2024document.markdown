---
layout: publication
title: 'DSLR: Document Refinement With Sentence-level Re-ranking And Reconstruction To Enhance Retrieval-augmented Generation'
authors: Taeho Hwang, Soyeong Jeong, Sukmin Cho, Seungyoon Han, Jong C. Park
conference: "KnowledgeNLP@ACL 2024"
year: 2024
bibkey: hwang2024document
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.03627'}
tags: ['Training Techniques', 'RAG', 'Tools']
---
Recent advancements in Large Language Models (LLMs) have significantly
improved their performance across various Natural Language Processing (NLP)
tasks. However, LLMs still struggle with generating non-factual responses due
to limitations in their parametric memory. Retrieval-Augmented Generation (RAG)
systems address this issue by incorporating external knowledge with a retrieval
module. Despite their successes, however, current RAG systems face challenges
with retrieval failures and the limited ability of LLMs to filter out
irrelevant information. Therefore, in this work, we propose DSLR (Document
Refinement with Sentence-Level Re-ranking and Reconstruction), an unsupervised
framework that decomposes retrieved documents into sentences, filters out
irrelevant sentences, and reconstructs them again into coherent passages. We
experimentally validate DSLR on multiple open-domain QA datasets and the
results demonstrate that DSLR significantly enhances the RAG performance over
conventional fixed-size passage. Furthermore, our DSLR enhances performance in
specific, yet realistic scenarios without the need for additional training,
providing an effective and efficient solution for refining retrieved documents
in RAG systems.
