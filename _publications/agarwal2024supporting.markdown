---
layout: publication
title: 'Llm+reasoning+planning For Supporting Incomplete User Queries In Presence Of Apis'
authors: Sudhir Intuit Inc. Agarwal, Anu Intuit Inc. Sreepathy, David H. Intuit Inc. Alonso, Prarit Intuit Inc. Lamba
conference: "EPTCS 416 2025 pp. 29-58"
year: 2024
bibkey: agarwal2024supporting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12433"}
tags: ['RAG', 'Tools', 'Reinforcement Learning']
---
Recent availability of Large Language Models (LLMs) has led to the
development of numerous LLM-based approaches aimed at providing natural
language interfaces for various end-user tasks. These end-user tasks in turn
can typically be accomplished by orchestrating a given set of APIs. In
practice, natural language task requests (user queries) are often incomplete,
i.e., they may not contain all the information required by the APIs. While LLMs
excel at natural language processing (NLP) tasks, they frequently hallucinate
on missing information or struggle with orchestrating the APIs. The key idea
behind our proposed approach is to leverage logical reasoning and classical AI
planning along with an LLM for accurately answering user queries including
identification and gathering of any missing information in these queries. Our
approach uses an LLM and ASP (Answer Set Programming) solver to translate a
user query to a representation in Planning Domain Definition Language (PDDL)
via an intermediate representation in ASP. We introduce a special API
"get_info_api" for gathering missing information. We model all the APIs as PDDL
actions in a way that supports dataflow between the APIs. Our approach then
uses a classical AI planner to generate an orchestration of API calls
(including calls to get_info_api) to answer the user query. Our evaluation
results show that our approach significantly outperforms a pure LLM based
approach by achieving over 95% success rate in most cases on a dataset
containing complete and incomplete single goal and multi-goal queries where the
multi-goal queries may or may not require dataflow among the APIs.
