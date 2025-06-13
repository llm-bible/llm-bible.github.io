---
layout: publication
title: 'Proprag: Guiding Retrieval With Beam Search Over Proposition Paths'
authors: Jingjin Wang
conference: "Arxiv"
year: 2025
bibkey: wang2025guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18070"}
tags: ['RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) has become the standard non-parametric
approach for equipping Large Language Models (LLMs) with up-to-date knowledge
and mitigating catastrophic forgetting common in continual learning. However,
standard RAG, relying on independent passage retrieval, fails to capture the
interconnected nature of human memory crucial for complex reasoning
(associativity) and contextual understanding (sense-making). While structured
RAG methods like HippoRAG utilize knowledge graphs (KGs) built from triples,
the inherent context loss limits fidelity. We introduce PropRAG, a framework
leveraging contextually rich propositions and a novel beam search algorithm
over proposition paths to explicitly discover multi-step reasoning chains.
Crucially, PropRAG's online retrieval process operates entirely without
invoking generative LLMs, relying instead on efficient graph traversal and
pre-computed embeddings. This avoids online LLM inference costs and potential
inconsistencies during evidence gathering. LLMs are used effectively offline
for high-quality proposition extraction and post-retrieval for answer
generation. PropRAG achieves state-of-the-art zero-shot Recall@5 results on
PopQA (55.3%), 2Wiki (93.7%), HotpotQA (97.0%), and MuSiQue (77.3%), alongside
top F1 scores (e.g., 52.4% on MuSiQue). By improving evidence retrieval through
richer representation and explicit, LLM-free online path finding, PropRAG
advances non-parametric continual learning.
