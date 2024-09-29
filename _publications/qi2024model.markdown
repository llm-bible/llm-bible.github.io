---
layout: publication
title: Model Internals45;based Answer Attribution For Trustworthy Retrieval45;augmented Generation
authors: Qi Jirui, Sarti Gabriele, Fernández Raquel, Bisazza Arianna
conference: "Arxiv"
year: 2024
bibkey: qi2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13663"}
tags: ['Applications', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Ensuring the verifiability of model answers is a fundamental challenge for retrieval45;augmented generation (RAG) in the question answering (QA) domain. Recently self45;citation prompting was proposed to make large language models (LLMs) generate citations to supporting documents along with their answers. However self45;citing LLMs often struggle to match the required format refer to non45;existent sources and fail to faithfully reflect LLMs context usage throughout the generation. In this work we present MIRAGE 45;45;Model Internals45;based RAG Explanations 45;45; a plug45;and45;play approach using model internals for faithful answer attribution in RAG applications. MIRAGE detects context45;sensitive answer tokens and pairs them with retrieved documents contributing to their prediction via saliency methods. We evaluate our proposed approach on a multilingual extractive QA dataset finding high agreement with human answer attribution. On open45;ended QA MIRAGE achieves citation quality and efficiency comparable to self45;citation while also allowing for a finer45;grained control of attribution parameters. Our qualitative evaluation highlights the faithfulness of MIRAGEs attributions and underscores the promising application of model internals for RAG answer attribution.
