---
layout: publication
title: 'Elevating Legal LLM Responses: Harnessing Trainable Logical Structures And Semantic Knowledge With Legal Reasoning'
authors: Rujing Yao, Yang Wu, Chenghao Wang, Jingwei Xiong, Fang Wang, Xiaozhong Liu
conference: "Arxiv"
year: 2025
bibkey: yao2025elevating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.07912'}
tags: ['Agentic', 'RAG', 'Tools', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Large Language Models (LLMs) have achieved impressive results across numerous
domains, yet they experience notable deficiencies in legal question-answering
tasks. LLMs often generate generalized responses that lack the logical
specificity required for expert legal advice and are prone to hallucination,
providing answers that appear correct but are unreliable. Retrieval-Augmented
Generation (RAG) techniques offer partial solutions to address this challenge,
but existing approaches typically focus only on semantic similarity, neglecting
the logical structure essential to legal reasoning. In this paper, we propose
the Logical-Semantic Integration Model (LSIM), a novel supervised framework
that bridges semantic and logical coherence. LSIM comprises three components:
reinforcement learning predicts a structured fact-rule chain for each question,
a trainable Deep Structured Semantic Model (DSSM) retrieves the most relevant
candidate questions by integrating semantic and logical features, and
in-context learning generates the final answer using the retrieved content. Our
experiments on a real-world legal QA dataset-validated through both automated
metrics and human evaluation-demonstrate that LSIM significantly enhances
accuracy and reliability compared to existing methods.
