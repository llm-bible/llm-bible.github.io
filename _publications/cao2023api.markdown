---
layout: publication
title: 'Api-assisted Code Generation For Question Answering On Varied Table Structures'
authors: Yihan Cao, Shuyi Chen, Ryan Liu, Zhiruo Wang, Daniel Fried
conference: "Proceedings of the Conference on Empirical Methods in Natural Language Processing Association for Computational Linguistics 2023 pages 14536-14548 Singapore"
year: 2023
bibkey: cao2023api
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14687"}
tags: ['Tools', 'Applications', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
A persistent challenge to table question answering (TableQA) by generating
executable programs has been adapting to varied table structures, typically
requiring domain-specific logical forms. In response, this paper introduces a
unified TableQA framework that: (1) provides a unified representation for
structured tables as multi-index Pandas data frames, (2) uses Python as a
powerful querying language, and (3) uses few-shot prompting to translate NL
questions into Python programs, which are executable on Pandas data frames.
Furthermore, to answer complex relational questions with extended program
functionality and external knowledge, our framework allows customized APIs that
Python programs can call. We experiment with four TableQA datasets that involve
tables of different structures -- relational, multi-table, and hierarchical
matrix shapes -- and achieve prominent improvements over past state-of-the-art
systems. In ablation studies, we (1) show benefits from our multi-index
representation and APIs over baselines that use only an LLM, and (2)
demonstrate that our approach is modular and can incorporate additional APIs.
