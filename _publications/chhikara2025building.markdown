---
layout: publication
title: 'Mem0: Building Production-ready AI Agents With Scalable Long-term Memory'
authors: Prateek Chhikara, Dev Khant, Saket Aryan, Taranjeet Singh, Deshraj Yadav
conference: "Arxiv"
year: 2025
bibkey: chhikara2025building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19413"}
tags: ['RAG', 'Agentic', 'Model Architecture', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable prowess in
generating contextually coherent responses, yet their fixed context windows
pose fundamental challenges for maintaining consistency over prolonged
multi-session dialogues. We introduce Mem0, a scalable memory-centric
architecture that addresses this issue by dynamically extracting,
consolidating, and retrieving salient information from ongoing conversations.
Building on this foundation, we further propose an enhanced variant that
leverages graph-based memory representations to capture complex relational
structures among conversational elements. Through comprehensive evaluations on
LOCOMO benchmark, we systematically compare our approaches against six baseline
categories: (i) established memory-augmented systems, (ii) retrieval-augmented
generation (RAG) with varying chunk sizes and k-values, (iii) a full-context
approach that processes the entire conversation history, (iv) an open-source
memory solution, (v) a proprietary model system, and (vi) a dedicated memory
management platform. Empirical results show that our methods consistently
outperform all existing memory systems across four question categories:
single-hop, temporal, multi-hop, and open-domain. Notably, Mem0 achieves 26%
relative improvements in the LLM-as-a-Judge metric over OpenAI, while Mem0 with
graph memory achieves around 2% higher overall score than the base
configuration. Beyond accuracy gains, we also markedly reduce computational
overhead compared to full-context method. In particular, Mem0 attains a 91%
lower p95 latency and saves more than 90% token cost, offering a compelling
balance between advanced reasoning capabilities and practical deployment
constraints. Our findings highlight critical role of structured, persistent
memory mechanisms for long-term conversational coherence, paving the way for
more reliable and efficient LLM-driven AI agents.
