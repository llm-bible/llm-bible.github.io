---
layout: publication
title: 'Retrieval-augmented Test Generation: How Far Are We?'
authors: Jiho Shin, Reem Aleithan, Hadi Hemmati, Song Wang
conference: "Arxiv"
year: 2024
bibkey: shin2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12682"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Prompting']
---
Retrieval Augmented Generation (RAG) has shown notable advancements in
software engineering tasks. Despite its potential, RAG's application in unit
test generation remains under-explored. To bridge this gap, we take the
initiative to investigate the efficacy of RAG-based LLMs in test generation. As
RAGs can leverage various knowledge sources to enhance their performance, we
also explore the impact of different sources of RAGs' knowledge bases on unit
test generation to provide insights into their practical benefits and
limitations. Specifically, we examine RAG built upon three types of domain
knowledge: 1) API documentation, 2) GitHub issues, and 3) StackOverflow Q&As.
Each source offers essential knowledge for creating tests from different
perspectives, i.e., API documentations provide official API usage guidelines,
GitHub issues offer resolutions of issues related to the APIs from the library
developers, and StackOverflow Q&As present community-driven solutions and best
practices. For our experiment, we focus on five widely used and typical
Python-based machine learning (ML) projects, i.e., TensorFlow, PyTorch,
Scikit-learn, Google JAX, and XGBoost to build, train, and deploy complex
neural networks efficiently. We conducted experiments using the top 10% most
widely used APIs across these projects, involving a total of 188 APIs. We
investigate the effectiveness of four state-of-the-art LLMs (open and
closed-sourced), i.e., GPT-3.5-Turbo, GPT-4o, Mistral MoE 8x22B, and Llamma 3.1
405B. Additionally, we compare three prompting strategies in generating unit
test cases for the experimental APIs, i.e., zero-shot, a Basic RAG, and an
API-level RAG on the three external sources. Finally, we compare the cost of
different sources of knowledge used for the RAG.
