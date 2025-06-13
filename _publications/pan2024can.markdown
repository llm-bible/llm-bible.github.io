---
layout: publication
title: 'Can Language Models Enable In-context Database?'
authors: Yu Pan, Hongfeng Yu, Tianjiao Zhao, Jianxin Sun
conference: "Arxiv"
year: 2024
bibkey: pan2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01807"}
tags: ['Applications', 'RAG', 'Merging', 'Few-Shot', 'Prompting']
---
Large language models (LLMs) are emerging as few-shot learners capable of
handling a variety of tasks, including comprehension, planning, reasoning,
question answering, arithmetic calculations, and more. At the core of these
capabilities is LLMs' proficiency in representing and understanding structural
or semi-structural data, such as tables and graphs. Numerous studies have
demonstrated that reasoning on tabular data or graphs is not only feasible for
LLMs but also gives a promising research direction which treats these data as
in-context data. The lightweight and human readable characteristics of
in-context database can potentially make it an alternative for the traditional
database in typical RAG (Retrieval Augmented Generation) settings. However,
almost all current work focuses on static in-context data, which does not allow
dynamic update. In this paper, to enable dynamic database update, delta
encoding of database is proposed. We explore how data stored in traditional
RDBMS can be encoded as in-context text and evaluate LLMs' proficiency for CRUD
(Create, Read, Update and Delete) operations on in-context databases. A
benchmark named InConDB is presented and extensive experiments are conducted to
show the performance of different language models in enabling in-context
database by varying the database encoding method, prompting method, operation
type and input data distribution, revealing both the proficiency and
limitations.
