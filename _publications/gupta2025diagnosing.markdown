---
layout: publication
title: 'Novelhopqa: Diagnosing Multi-hop Reasoning Failures In Long Narrative Contexts'
authors: Abhay Gupta, Michael Lu, Kevin Zhu, Sean O'brien, Vasu Sharma
conference: "Arxiv"
year: 2025
bibkey: gupta2025diagnosing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02000"}
tags: ['ACL']
---
Current large language models (LLMs) struggle to answer questions that span tens of thousands of tokens, especially when multi-hop reasoning is involved. While prior benchmarks explore long-context comprehension or multi-hop reasoning in isolation, none jointly vary context length and reasoning depth in natural narrative settings. We introduce NovelHopQA, the first benchmark to evaluate k1-4 hop QA over 64k-128k-token excerpts from 83 full-length public-domain novels. A keyword-guided pipeline builds hop-separated chains grounded in coherent storylines. We evaluate six state-of-the-art (SOTA) models and apply oracle-context filtering to ensure all questions are genuinely answerable. Human annotators validate both alignment and hop depth. We noticed consistent accuracy drops with increased hops and context length, even in frontier models-revealing that sheer scale does not guarantee robust reasoning. Our failure mode analysis highlights common breakdowns, such as missed final-hop integration and long-range drift. NovelHopQA offers a controlled diagnostic setting to stress-test multi-hop reasoning at scale.
