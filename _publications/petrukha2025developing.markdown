---
layout: publication
title: 'Swifteval: Developing A Language-specific Benchmark For Llm-generated Code Evaluation'
authors: Ivan Petrukha, Yana Kurliak, Nataliia Stulova
conference: "Arxiv"
year: 2025
bibkey: petrukha2025developing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24324"}
tags: ['Applications', 'Tools']
---
In recent years, large language models (LLMs) have showcased significant advancements in code generation. However, most evaluation benchmarks are primarily oriented towards Python, making it difficult to evaluate other programming languages, such as Swift, with high quality. By examining widely established multilingual benchmarks like HumanEval-XL and MultiPL-E, we identified critical issues specific to their Swift components, making them insufficient or even irrelevant for assessing LLM coding capabilities on Swift. Unlike these existing approaches, which prioritize rapid scaling and generalization by automatically translating Python-centric benchmarks with LLMs, we adopt a quality-over-quantity methodology. We present SwiftEval, the first Swift-oriented benchmark consisting of 28 carefully hand-crafted problems, and evaluate 44 popular Code LLMs on it. Our results show significant LLM scores drop for problems requiring language-specific features, most noticeable in the models of smaller sizes.
