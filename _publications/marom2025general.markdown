---
layout: publication
title: 'A General Retrieval-augmented Generation Framework For Multimodal Case-based Reasoning Applications'
authors: Ofir Marom
conference: "Arxiv"
year: 2025
bibkey: marom2025general
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.05030'}
tags: ['RAG', 'Applications', 'Tools', 'Multimodal Models', 'Reinforcement Learning']
---
Case-based reasoning (CBR) is an experience-based approach to problem
solving, where a repository of solved cases is adapted to solve new cases.
Recent research shows that Large Language Models (LLMs) with
Retrieval-Augmented Generation (RAG) can support the Retrieve and Reuse stages
of the CBR pipeline by retrieving similar cases and using them as additional
context to an LLM query. Most studies have focused on text-only applications,
however, in many real-world problems the components of a case are multimodal.
In this paper we present MCBR-RAG, a general RAG framework for multimodal CBR
applications. The MCBR-RAG framework converts non-text case components into
text-based representations, allowing it to: 1) learn application-specific
latent representations that can be indexed for retrieval, and 2) enrich the
query provided to the LLM by incorporating all case components for better
context. We demonstrate MCBR-RAG's effectiveness through experiments conducted
on a simplified Math-24 application and a more complex Backgammon application.
Our empirical results show that MCBR-RAG improves generation quality compared
to a baseline LLM with no contextual information provided.
