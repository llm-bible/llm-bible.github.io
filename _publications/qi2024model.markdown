---
layout: publication
title: 'Model Internals-based Answer Attribution For Trustworthy Retrieval-augmented Generation'
authors: Jirui Qi, Gabriele Sarti, Raquel Fernández, Arianna Bisazza
conference: "Proceedings of EMNLP (2024) 6037-6053"
year: 2024
bibkey: qi2024model
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13663'}
tags: ['Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Applications', 'Prompting', 'Reinforcement Learning']
---
Ensuring the verifiability of model answers is a fundamental challenge for
retrieval-augmented generation (RAG) in the question answering (QA) domain.
Recently, self-citation prompting was proposed to make large language models
(LLMs) generate citations to supporting documents along with their answers.
However, self-citing LLMs often struggle to match the required format, refer to
non-existent sources, and fail to faithfully reflect LLMs' context usage
throughout the generation. In this work, we present MIRAGE --Model
Internals-based RAG Explanations -- a plug-and-play approach using model
internals for faithful answer attribution in RAG applications. MIRAGE detects
context-sensitive answer tokens and pairs them with retrieved documents
contributing to their prediction via saliency methods. We evaluate our proposed
approach on a multilingual extractive QA dataset, finding high agreement with
human answer attribution. On open-ended QA, MIRAGE achieves citation quality
and efficiency comparable to self-citation while also allowing for a
finer-grained control of attribution parameters. Our qualitative evaluation
highlights the faithfulness of MIRAGE's attributions and underscores the
promising application of model internals for RAG answer attribution.
