---
layout: publication
title: 'Out Of Style: Rag''s Fragility To Linguistic Variation'
authors: Tianyu Cao, Neel Bhandari, Akhila Yerukola, Akari Asai, Maarten Sap
conference: "Arxiv"
year: 2025
bibkey: cao2025out
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08231"}
tags: ['RAG', 'Security', 'Applications', 'Reinforcement Learning']
---
Despite the impressive performance of Retrieval-augmented Generation (RAG)
systems across various NLP benchmarks, their robustness in handling real-world
user-LLM interaction queries remains largely underexplored. This presents a
critical gap for practical deployment, where user queries exhibit greater
linguistic variations and can trigger cascading errors across interdependent
RAG components. In this work, we systematically analyze how varying four
linguistic dimensions (formality, readability, politeness, and grammatical
correctness) impact RAG performance. We evaluate two retrieval models and nine
LLMs, ranging from 3 to 72 billion parameters, across four information-seeking
Question Answering (QA) datasets. Our results reveal that linguistic
reformulations significantly impact both retrieval and generation stages,
leading to a relative performance drop of up to 40.41% in Recall@5 scores for
less formal queries and 38.86% in answer match scores for queries containing
grammatical errors. Notably, RAG systems exhibit greater sensitivity to such
variations compared to LLM-only generations, highlighting their vulnerability
to error propagation due to linguistic shifts. These findings highlight the
need for improved robustness techniques to enhance reliability in diverse user
interactions.
