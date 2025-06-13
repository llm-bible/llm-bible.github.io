---
layout: publication
title: 'Pseudo-relevance Feedback Can Improve Zero-shot Llm-based Dense Retrieval'
authors: Hang Li, Xiao Wang, Bevan Koopman, Guido Zuccon
conference: "Arxiv"
year: 2025
bibkey: li2025pseudo
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.14887'}
tags: ['RAG', 'Prompting']
---
Pseudo-relevance feedback (PRF) refines queries by leveraging initially
retrieved documents to improve retrieval effectiveness. In this paper, we
investigate how large language models (LLMs) can facilitate PRF for zero-shot
LLM-based dense retrieval, extending the recently proposed PromptReps method.
Specifically, our approach uses LLMs to extract salient passage features-such
as keywords and summaries-from top-ranked documents, which are then integrated
into PromptReps to produce enhanced query representations. Experiments on
passage retrieval benchmarks demonstrate that incorporating PRF significantly
boosts retrieval performance. Notably, smaller rankers with PRF can match the
effectiveness of larger rankers without PRF, highlighting PRF's potential to
improve LLM-driven search while maintaining an efficient balance between
effectiveness and resource usage.
