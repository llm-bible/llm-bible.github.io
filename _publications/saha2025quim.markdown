---
layout: publication
title: 'Quim-rag: Advancing Retrieval-augmented Generation With Inverted Question Matching For Enhanced QA Performance'
authors: Binita Saha, Utsha Saha, Muhammad Zubair Malik
conference: "in IEEE Access vol. 12 pp. 185401-185410 2024"
year: 2025
bibkey: saha2025quim
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02702"}
tags: ['Model Architecture', 'Tools', 'RAG', 'BERT', 'Applications']
---
This work presents a novel architecture for building Retrieval-Augmented
Generation (RAG) systems to improve Question Answering (QA) tasks from a target
corpus. Large Language Models (LLMs) have revolutionized the analyzing and
generation of human-like text. These models rely on pre-trained data and lack
real-time updates unless integrated with live data tools. RAG enhances LLMs by
integrating online resources and databases to generate contextually appropriate
responses. However, traditional RAG still encounters challenges like
information dilution and hallucinations when handling vast amounts of data. Our
approach addresses these challenges by converting corpora into a
domain-specific dataset and RAG architecture is constructed to generate
responses from the target document. We introduce QuIM-RAG (Question-to-question
Inverted Index Matching), a novel approach for the retrieval mechanism in our
system. This strategy generates potential questions from document chunks and
matches these with user queries to identify the most relevant text chunks for
generating accurate answers. We have implemented our RAG system on top of the
open-source Meta-LLaMA3-8B-instruct model by Meta Inc. that is available on
Hugging Face. We constructed a custom corpus of 500+ pages from a high-traffic
website accessed thousands of times daily for answering complex questions,
along with manually prepared ground truth QA for evaluation. We compared our
approach with traditional RAG models using BERT-Score and RAGAS,
state-of-the-art metrics for evaluating LLM applications. Our evaluation
demonstrates that our approach outperforms traditional RAG architectures on
both metrics.
