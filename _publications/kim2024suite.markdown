---
layout: publication
title: 'SEAL: Suite For Evaluating Api-use Of Llms'
authors: Woojeong Kim, Ashish Jagmohan, Aditya Vempaty
conference: "Arxiv"
year: 2024
bibkey: kim2024suite
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15523'}
tags: ['Agentic', 'RAG', 'Model Architecture', 'GPT', 'Tools', 'Reinforcement Learning']
---
Large language models (LLMs) have limitations in handling tasks that require
real-time access to external APIs. While several benchmarks like ToolBench and
APIGen have been developed to assess LLMs' API-use capabilities, they often
suffer from issues such as lack of generalizability, limited multi-step
reasoning coverage, and instability due to real-time API fluctuations. In this
paper, we introduce SEAL, an end-to-end testbed designed to evaluate LLMs in
real-world API usage. SEAL standardizes existing benchmarks, integrates an
agent system for testing API retrieval and planning, and addresses the
instability of real-time APIs by introducing a GPT-4-powered API simulator with
caching for deterministic evaluations. Our testbed provides a comprehensive
evaluation pipeline that covers API retrieval, API calls, and final responses,
offering a reliable framework for structured performance comparison in diverse
real-world scenarios. SEAL is publicly available, with ongoing updates for new
benchmarks.
