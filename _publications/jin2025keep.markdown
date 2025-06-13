---
layout: publication
title: '"well, Keep Thinking": Enhancing LLM Reasoning With Adaptive Injection Decoding'
authors: Hyunbin Jin, Je Won Yeom, Seunghyun Bae, Taesup Kim
conference: "Arxiv"
year: 2025
bibkey: jin2025keep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10167"}
tags: ['Prompting', 'Few-Shot']
---
Large language models (LLMs) exhibit strong reasoning abilities, often
attributed to few-shot or zero-shot chain-of-thought (CoT) prompting. While
effective, these methods require labor-intensive prompt engineering, raising
the question of whether reasoning can be induced without reliance on explicit
prompts. In this work, we unlock the reasoning capabilities of LLMs without
explicit prompting. Inspired by zero-shot CoT and CoT-decoding, we propose a
novel decoding strategy that systematically nudges LLMs to continue reasoning,
thereby preventing immature reasoning processes. Specifically, we monitor the
model's generation and inject a designated phrase whenever it is likely to
conclude its response prematurely, before completing the reasoning process. Our
experimental evaluations on diverse reasoning benchmarks demonstrate that our
proposed strategy substantially improves LLM reasoning capabilities,
highlighting the potential of decoding-based interventions as an alternative to
traditional prompting techniques.
