---
layout: publication
title: 'Building A Coding Assistant Via The Retrieval-augmented Language Model'
authors: Xinze Li, Hanbin Wang, Zhenghao Liu, Shi Yu, Shuo Wang, Yukun Yan, Yukai Fu, Yu Gu, Ge Yu
conference: "Arxiv"
year: 2024
bibkey: li2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16229"}
tags: ['Prompting', 'RAG', 'Applications']
---
Pretrained language models have shown strong effectiveness in code-related
tasks, such as code retrieval, code generation, code summarization, and code
completion tasks. In this paper, we propose COde assistaNt viA
retrieval-augmeNted language model (CONAN), which aims to build a code
assistant by mimicking the knowledge-seeking behaviors of humans during coding.
Specifically, it consists of a code structure aware retriever (CONAN-R) and a
dual-view code representation-based retrieval-augmented generation model
(CONAN-G). CONAN-R pretrains CodeT5 using Code-Documentation Alignment and
Masked Entity Prediction tasks to make language models code structure-aware and
learn effective representations for code snippets and documentation. Then
CONAN-G designs a dual-view code representation mechanism for implementing a
retrieval-augmented code generation model. CONAN-G regards the code
documentation descriptions as prompts, which help language models better
understand the code semantics. Our experiments show that CONAN achieves
convincing performance on different code generation tasks and significantly
outperforms previous retrieval augmented code generation models. Our further
analyses show that CONAN learns tailored representations for both code snippets
and documentation by aligning code-documentation data pairs and capturing
structural semantics by masking and predicting entities in the code data.
Additionally, the retrieved code snippets and documentation provide necessary
information from both program language and natural language to assist the code
generation process. CONAN can also be used as an assistant for Large Language
Models (LLMs), providing LLMs with external knowledge in shorter code document
lengths to improve their effectiveness on various code tasks. It shows the
ability of CONAN to extract necessary information and help filter out the noise
from retrieved code documents.
