---
layout: publication
title: 'Knowing When To Stop: Dynamic Context Cutoff For Large Language Models'
authors: Roy Xie, Junlin Wang, Paul Rosu, Chunyuan Deng, Bolun Sun, Zihao Lin, Bhuwan Dhingra
conference: "Arxiv"
year: 2025
bibkey: xie2025knowing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01025"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'Prompting', 'Attention Mechanism']
---
Large language models (LLMs) process entire input contexts indiscriminately,
which is inefficient in cases where the information required to answer a query
is localized within the context. We present dynamic context cutoff, a
human-inspired method enabling LLMs to self-terminate processing upon acquiring
sufficient task-relevant information. Through analysis of model internals, we
discover that specific attention heads inherently encode "sufficiency signals"
- detectable through lightweight classifiers - that predict when critical
information has been processed. This reveals a new efficiency paradigm: models'
internal understanding naturally dictates processing needs rather than external
compression heuristics. Comprehensive experiments across six QA datasets (up to
40K tokens) with three model families (LLaMA/Qwen/Mistral, 1B0-70B) demonstrate
1.33x average token reduction while improving accuracy by 1.3%. Furthermore,
our method demonstrates better performance with the same rate of token
reduction compared to other context efficiency methods. Additionally, we
observe an emergent scaling phenomenon: while smaller models require require
probing for sufficiency detection, larger models exhibit intrinsic
self-assessment capabilities through prompting.
