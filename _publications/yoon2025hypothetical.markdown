---
layout: publication
title: 'Hypothetical Documents Or Knowledge Leakage? Rethinking Llm-based Query Expansion'
authors: Yejun Yoon, Jaeyoon Jung, Seunghyun Yoon, Kunwoo Park
conference: "Arxiv"
year: 2025
bibkey: yoon2025hypothetical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14175'}
tags: ['RAG']
---
Query expansion methods powered by large language models (LLMs) have demonstrated effectiveness in zero-shot retrieval tasks. These methods assume that LLMs can generate hypothetical documents that, when incorporated into a query vector, enhance the retrieval of real evidence. However, we challenge this assumption by investigating whether knowledge leakage in benchmarks contributes to the observed performance gains. Using fact verification as a testbed, we analyze whether the generated documents contain information entailed by ground-truth evidence and assess their impact on performance. Our findings indicate that, on average, performance improvements consistently occurred for claims whose generated documents included sentences entailed by gold evidence. This suggests that knowledge leakage may be present in fact-verification benchmarks, potentially inflating the perceived performance of LLM-based query expansion methods.
