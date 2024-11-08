---
layout: publication
title: 'ERATTA: Extreme RAG For Table To Answers With Large Language Models'
authors: Roychowdhury Sohini, Krema Marko, Mahammad Anvar, Moore Brian, Mukherjee Arijit, Prakashchandra Punit
conference: "Arxiv"
year: 2024
bibkey: roychowdhury2024extreme
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03963"}
tags: ['Agentic', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Large language models (LLMs) with retrieval augmented-generation (RAG) have
been the optimal choice for scalable generative AI solutions in the recent
past. Although RAG implemented with AI agents (agentic-RAG) has been recently
popularized, its suffers from unstable cost and unreliable performances for
Enterprise-level data-practices. Most existing use-cases that incorporate RAG
with LLMs have been either generic or extremely domain specific, thereby
questioning the scalability and generalizability of RAG-LLM approaches. In this
work, we propose a unique LLM-based system where multiple LLMs can be invoked
to enable data authentication, user-query routing, data-retrieval and custom
prompting for question-answering capabilities from Enterprise-data tables. The
source tables here are highly fluctuating and large in size and the proposed
framework enables structured responses in under 10 seconds per query.
Additionally, we propose a five metric scoring module that detects and reports
hallucinations in the LLM responses. Our proposed system and scoring metrics
achieve >90% confidence scores across hundreds of user queries in the
sustainability, financial health and social media domains. Extensions to the
proposed extreme RAG architectures can enable heterogeneous source querying
using LLMs.
