---
layout: publication
title: 'Forbidden Science: Dual-use AI Challenge Benchmark And Scientific Refusal Tests'
authors: David Noever, Forrest Mckee
conference: "Arxiv"
year: 2025
bibkey: noever2025forbidden
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06867"}
tags: ['Responsible AI', 'Model Architecture', 'Tools', 'GPT', 'Prompting']
---
The development of robust safety benchmarks for large language models
requires open, reproducible datasets that can measure both appropriate refusal
of harmful content and potential over-restriction of legitimate scientific
discourse. We present an open-source dataset and testing framework for
evaluating LLM safety mechanisms across mainly controlled substance queries,
analyzing four major models' responses to systematically varied prompts. Our
results reveal distinct safety profiles: Claude-3.5-sonnet demonstrated the
most conservative approach with 73% refusals and 27% allowances, while Mistral
attempted to answer 100% of queries. GPT-3.5-turbo showed moderate restriction
with 10% refusals and 90% allowances, and Grok-2 registered 20% refusals and
80% allowances. Testing prompt variation strategies revealed decreasing
response consistency, from 85% with single prompts to 65% with five variations.
This publicly available benchmark enables systematic evaluation of the critical
balance between necessary safety restrictions and potential over-censorship of
legitimate scientific inquiry, while providing a foundation for measuring
progress in AI safety implementation. Chain-of-thought analysis reveals
potential vulnerabilities in safety mechanisms, highlighting the complexity of
implementing robust safeguards without unduly restricting desirable and valid
scientific discourse.
