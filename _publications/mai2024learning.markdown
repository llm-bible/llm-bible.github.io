---
layout: publication
title: 'Learning Metadata-agnostic Representations For Text-to-sql In-context Example Selection'
authors: Chuhong Mai, Ro-ee Tal, Thahir Mohamed
conference: "Arxiv"
year: 2024
bibkey: mai2024learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14049'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) is a powerful paradigm where large language models
(LLMs) benefit from task demonstrations added to the prompt. Yet, selecting
optimal demonstrations is not trivial, especially for complex or multi-modal
tasks where input and output distributions differ. We hypothesize that forming
task-specific representations of the input is key. In this paper, we propose a
method to align representations of natural language questions and those of SQL
queries in a shared embedding space. Our technique, dubbed MARLO -
Metadata-Agnostic Representation Learning for Text-tO-SQL - uses query
structure to model querying intent without over-indexing on underlying database
metadata (i.e. tables, columns, or domain-specific entities of a database
referenced in the question or query). This allows MARLO to select examples that
are structurally and semantically relevant for the task rather than examples
that are spuriously related to a certain domain or question phrasing. When used
to retrieve examples based on question similarity, MARLO shows superior
performance compared to generic embedding models (on average +2.9%pt. in
execution accuracy) on the Spider benchmark. It also outperforms the next best
method that masks metadata information by +0.8%pt. in execution accuracy on
average, while imposing a significantly lower inference latency.
