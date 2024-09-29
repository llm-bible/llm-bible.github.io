---
layout: publication
title: Furthest Reasoning With Plan Assessment Stable Reasoning Path With Retrieval45;augmented Large Language Models
authors: Zhu Yin, Luo Zhiling, Cheng Gong
conference: "Arxiv"
year: 2023
bibkey: zhu2023furthest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.12767"}
tags: ['Applications', 'RAG', 'Tools']
---
Large Language Models (LLMs) acting as a powerful reasoner and generator exhibit extraordinary performance across various natural language tasks such as question answering (QA). Among these tasks Multi45;Hop Question Answering (MHQA) stands as a widely discussed category necessitating seamless integration between LLMs and the retrieval of external knowledge. Existing methods employ LLM to generate reasoning paths and plans and utilize IR to iteratively retrieve related knowledge but these approaches have inherent flaws. On one hand Information Retriever (IR) is hindered by the low quality of generated queries by LLM. On the other hand LLM is easily misguided by the irrelevant knowledge by IR. These inaccuracies accumulated by the iterative interaction between IR and LLM lead to a disaster in effectiveness at the end. To overcome above barriers in this paper we propose a novel pipeline for MHQA called Furthest45;Reasoning45;with45;Plan45;Assessment (FuRePA) including an improved framework (Furthest Reasoning) and an attached module (Plan Assessor). 1) Furthest reasoning operates by masking previous reasoning path and generated queries for LLM encouraging LLM generating chain of thought from scratch in each iteration. This approach enables LLM to break the shackle built by previous misleading thoughts and queries (if any). 2) The Plan Assessor is a trained evaluator that selects an appropriate plan from a group of candidate plans proposed by LLM. Our methods are evaluated on three highly recognized public multi45;hop question answering datasets and outperform state45;of45;the45;art on most metrics (achieving a 1037;45;1237; in answer accuracy).
