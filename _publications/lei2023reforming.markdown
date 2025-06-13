---
layout: publication
title: 'Instructerc: Reforming Emotion Recognition In Conversation With Multi-task Retrieval-augmented Large Language Models'
authors: Shanglin Lei, Guanting Dong, Xiaoping Wang, Keheng Wang, Runqi Qiao, Sirui Wang
conference: "Arxiv"
year: 2023
bibkey: lei2023reforming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11911"}
tags: ['Fine-Tuning', 'RAG', 'Tools']
---
The field of emotion recognition of conversation (ERC) has been focusing on
separating sentence feature encoding and context modeling, lacking exploration
in generative paradigms based on unified designs. In this study, we propose a
novel approach, InstructERC, to reformulate the ERC task from a discriminative
framework to a generative framework based on Large Language Models (LLMs).
InstructERC makes three significant contributions: (1) it introduces a simple
yet effective retrieval template module, which helps the model explicitly
integrate multi-granularity dialogue supervision information. (2) We introduce
two additional emotion alignment tasks, namely speaker identification and
emotion prediction tasks, to implicitly model the dialogue role relationships
and future emotional tendencies in conversations. (3) Pioneeringly, we unify
emotion labels across benchmarks through the feeling wheel to fit real
application scenarios. InstructERC still perform impressively on this unified
dataset. Our LLM-based plugin framework significantly outperforms all previous
models and achieves comprehensive SOTA on three commonly used ERC datasets.
Extensive analysis of parameter-efficient and data-scaling experiments provides
empirical guidance for applying it in practical scenarios.
