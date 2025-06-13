---
layout: publication
title: 'An Open-source Dual-loss Embedding Model For Semantic Retrieval In Higher Education'
authors: Ramteja Sajja, Yusuf Sermet, Ibrahim Demir
conference: "Arxiv"
year: 2025
bibkey: sajja2025open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.04916'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Recent advances in AI have catalyzed the adoption of intelligent educational
tools, yet many semantic retrieval systems remain ill-suited to the unique
linguistic and structural characteristics of academic content. This study
presents two open-source embedding models fine-tuned for educational question
answering, particularly in the context of course syllabi. A synthetic dataset
of 3,197 sentence pairs, spanning synonymous terminology, paraphrased
questions, and implicit-explicit mappings, was constructed through a
combination of manual curation and large language model (LLM)-assisted
generation. Two training strategies were evaluated: (1) a baseline model
fine-tuned using MultipleNegativesRankingLoss (MNRL), and (2) a dual-loss model
that combines MNRL with CosineSimilarityLoss to improve both semantic ranking
and similarity calibration. Evaluations were conducted on 28 university course
syllabi using a fixed set of natural language questions categorized into
course, faculty, and teaching assistant information. Results demonstrate that
both fine-tuned models outperform strong open-source baselines, including
all-MiniLM-L6-v2 and multi-qa-MiniLM-L6-cos-v1, and that the dual-loss model
narrows the performance gap with high-performing proprietary embeddings such as
OpenAI's text-embedding-3 series. This work contributes reusable,
domain-aligned embedding models and provides a replicable framework for
educational semantic retrieval, supporting downstream applications such as
academic chatbots, retrieval-augmented generation (RAG) systems, and learning
management system (LMS) integrations.
