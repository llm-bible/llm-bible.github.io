---
layout: publication
title: 'Tiny QA Benchmark++: Ultra-lightweight, Synthetic Multilingual Dataset Generation & Smoke-tests For Continuous LLM Evaluation'
authors: Vincent Koc
conference: "Arxiv"
year: 2025
bibkey: koc2025tiny
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12058'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
Tiny QA Benchmark++ (TQB++) presents an ultra-lightweight, multilingual smoke-test suite designed to give large-language-model (LLM) pipelines a unit-test style safety net dataset that runs in seconds with minimal cost. Born out of the tight feedback-loop demands building the Comet Opik prompt-optimization SDK, where waiting on heavyweight benchmarks breaks developer flow. TQB++ couples a 52-item English gold set (less than 20 kB) with a tiny synthetic-data generator pypi package built on provider-agnostic LiteLLM. The generator lets practitioners mint their own tiny packs in any language, domain, or difficulty, while ten ready-made packs already cover Arabic, Chinese, French, German, Japanese, Korean, Portuguese, Russian, Spanish, and Turkish. Every dataset ships with Croissant metadata and plug-and-play files for OpenAI-Evals, LangChain, and standard CI tools, so teams can drop deterministic micro-benchmarks directly into pull-request gates, prompt-engineering loops, and production dashboards without touching GPU budgets. A complete TQB++ run adds only a few seconds to pipeline latency yet reliably flags prompt-template errors, tokenizer drift, and fine-tuning side-effects long before full-scale suites like MMLU or BIG-Bench would finish configuring. The entire framework is released to accelerate continuous, resource-efficient quality assurance across the generative-AI ecosystem.
