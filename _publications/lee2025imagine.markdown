---
layout: publication
title: 'Imagine All The Relevance: Scenario-profiled Indexing With Knowledge Expansion For Dense Retrieval'
authors: Sangam Lee, Ryang Heo, Seongku Kang, Dongha Lee
conference: "Arxiv"
year: 2025
bibkey: lee2025imagine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23033'}
tags: ['RAG', 'Tools']
---
Existing dense retrieval models struggle with reasoning-intensive retrieval
task as they fail to capture implicit relevance that requires reasoning beyond
surface-level semantic information. To address these challenges, we propose
Scenario-Profiled Indexing with Knowledge Expansion (SPIKE), a dense retrieval
framework that explicitly indexes implicit relevance by decomposing documents
into scenario-based retrieval units. SPIKE organizes documents into scenario,
which encapsulates the reasoning process necessary to uncover implicit
relationships between hypothetical information needs and document content.
SPIKE constructs a scenario-augmented dataset using a powerful teacher large
language model (LLM), then distills these reasoning capabilities into a
smaller, efficient scenario generator. During inference, SPIKE incorporates
scenario-level relevance alongside document-level relevance, enabling
reasoning-aware retrieval. Extensive experiments demonstrate that SPIKE
consistently enhances retrieval performance across various query types and
dense retrievers. It also enhances the retrieval experience for users through
scenario and offers valuable contextual information for LLMs in
retrieval-augmented generation (RAG).
