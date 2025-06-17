---
layout: publication
title: 'Genegpt: Augmenting Large Language Models With Domain Tools For Improved Access
  To Biomedical Information'
authors: Qiao Jin, Yifan Yang, Qingyu Chen, Zhiyong Lu
conference: Bioinformatics 2024
year: 2023
citations: 67
bibkey: jin2023augmenting
additional_links:
- name: Paper
  url: https://arxiv.org/abs/2304.09667
tags:
- GPT
- In-Context Learning
- RAG
- Tools
- Prompting
---
While large language models (LLMs) have been successfully applied to various
tasks, they still face challenges with hallucinations. Augmenting LLMs with
domain-specific tools such as database utilities can facilitate easier and more
precise access to specialized knowledge. In this paper, we present GeneGPT, a
novel method for teaching LLMs to use the Web APIs of the National Center for
Biotechnology Information (NCBI) for answering genomics questions.
Specifically, we prompt Codex to solve the GeneTuring tests with NCBI Web APIs
by in-context learning and an augmented decoding algorithm that can detect and
execute API calls. Experimental results show that GeneGPT achieves
state-of-the-art performance on eight tasks in the GeneTuring benchmark with an
average score of 0.83, largely surpassing retrieval-augmented LLMs such as the
new Bing (0.44), biomedical LLMs such as BioMedLM (0.08) and BioGPT (0.04), as
well as GPT-3 (0.16) and ChatGPT (0.12). Our further analyses suggest that: (1)
API demonstrations have good cross-task generalizability and are more useful
than documentations for in-context learning; (2) GeneGPT can generalize to
longer chains of API calls and answer multi-hop questions in GeneHop, a novel
dataset introduced in this work; (3) Different types of errors are enriched in
different tasks, providing valuable insights for future improvements.