---
layout: publication
title: 'Truthflow: Truthful LLM Generation Via Representation Flow Correction'
authors: Hanyu Wang, Bochuan Cao, Yuanpu Cao, Jinghui Chen
conference: "Arxiv"
year: 2025
bibkey: wang2025truthful
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04556'}
tags: ['RAG']
---
Large language models (LLMs) are known to struggle with consistently
generating truthful responses. While various representation intervention
techniques have been proposed, these methods typically apply a universal
representation correction vector to all input queries, limiting their
effectiveness against diverse queries in practice. In this study, we introduce
TruthFlow, a novel method that leverages the Flow Matching technique for
query-specific truthful representation correction. Specifically, TruthFlow
first uses a flow model to learn query-specific correction vectors that
transition representations from hallucinated to truthful states. Then, during
inference, the trained flow model generates these correction vectors to enhance
the truthfulness of LLM outputs. Experimental results demonstrate that
TruthFlow significantly improves performance on open-ended generation tasks
across various advanced LLMs evaluated on TruthfulQA. Moreover, the trained
TruthFlow model exhibits strong transferability, performing effectively on
other unseen hallucination benchmarks.
