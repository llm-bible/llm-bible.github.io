---
layout: publication
title: 'RAG Without The Lag: Interactive Debugging For Retrieval-augmented Generation Pipelines'
authors: Quentin Romero Lauro, Shreya Shankar, Sepanta Zeighami, Aditya Parameswaran
conference: "Arxiv"
year: 2025
bibkey: lauro2025rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13587"}
tags: ['RAG', 'Tools']
---
Retrieval-augmented generation (RAG) pipelines have become the de-facto
approach for building AI assistants with access to external, domain-specific
knowledge. Given a user query, RAG pipelines typically first retrieve (R)
relevant information from external sources, before invoking a Large Language
Model (LLM), augmented (A) with this information, to generate (G) responses.
Modern RAG pipelines frequently chain multiple retrieval and generation
components, in any order. However, developing effective RAG pipelines is
challenging because retrieval and generation components are intertwined, making
it hard to identify which component(s) cause errors in the eventual output. The
parameters with the greatest impact on output quality often require hours of
pre-processing after each change, creating prohibitively slow feedback cycles.
To address these challenges, we present RAGGY, a developer tool that combines a
Python library of composable RAG primitives with an interactive interface for
real-time debugging. We contribute the design and implementation of RAGGY,
insights into expert debugging patterns through a qualitative study with 12
engineers, and design implications for future RAG tools that better align with
developers' natural workflows.
