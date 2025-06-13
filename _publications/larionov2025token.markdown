---
layout: publication
title: 'Batchgemba: Token-efficient Machine Translation Evaluation With Batched Prompting And Prompt Compression'
authors: Daniil Larionov, Steffen Eger
conference: "Arxiv"
year: 2025
bibkey: larionov2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02756"}
  - {name: "Code", url: "https://github.com/NL2G/batchgemba"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Has Code', 'Prompting']
---
Recent advancements in Large Language Model (LLM)-based Natural Language
Generation evaluation have largely focused on single-example prompting,
resulting in significant token overhead and computational inefficiencies. In
this work, we introduce BatchGEMBA-MQM, a framework that integrates batched
prompting with the GEMBA-MQM metric for machine translation evaluation. Our
approach aggregates multiple translation examples into a single prompt,
reducing token usage by 2-4 times (depending on the batch size) relative to
single-example prompting. Furthermore, we propose a batching-aware prompt
compression model that achieves an additional token reduction of 13-15% on
average while also showing ability to help mitigate batching-induced quality
degradation. Evaluations across several LLMs (GPT-4o, GPT-4o-mini, Mistral
Small, Phi4, and CommandR7B) and varying batch sizes reveal that while batching
generally negatively affects quality (but sometimes not substantially), prompt
compression does not degrade further, and in some cases, recovers quality loss.
For instance, GPT-4o retains over 90% of its baseline performance at a batch
size of 4 when compression is applied, compared to a 44.6% drop without
compression. We plan to release our code and trained models at
https://github.com/NL2G/batchgemba to support future research in this domain.
