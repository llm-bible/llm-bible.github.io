---
layout: publication
title: 'MARAGS: A Multi-adapter System For Multi-task Retrieval Augmented Generation Question Answering'
authors: Mitchell Dehaven
conference: "Arxiv"
year: 2024
bibkey: dehaven2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03171"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'KDD', 'Applications']
---
In this paper we present a multi-adapter retrieval augmented generation
system (MARAGS) for Meta's Comprehensive RAG (CRAG) competition for KDD CUP
2024. CRAG is a question answering dataset contains 3 different subtasks aimed
at realistic question and answering RAG related tasks, with a diverse set of
question topics, question types, time dynamic answers, and questions featuring
entities of varying popularity.
  Our system follows a standard setup for web based RAG, which uses processed
web pages to provide context for an LLM to produce generations, while also
querying API endpoints for additional information. MARAGS also utilizes
multiple different adapters to solve the various requirements for these tasks
with a standard cross-encoder model for ranking candidate passages relevant for
answering the question. Our system achieved 2nd place for Task 1 as well as 3rd
place on Task 2.
