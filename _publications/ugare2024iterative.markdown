---
layout: publication
title: 'Itergen: Iterative Semantic-aware Structured LLM Generation With Backtracking'
authors: Shubham Ugare, Rohan Gumaste, Tarun Suresh, Gagandeep Singh, Sasa Misailovic
conference: "Arxiv"
year: 2024
bibkey: ugare2024iterative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.07295'}
  - {name: "Code", url: 'https://structuredllm.com'}
tags: ['Has Code', 'RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) are widely used for tasks such as natural
language and code generation, but their outputs often suffer from issues like
hallucination, toxicity, and incorrect results. Current libraries for
structured LLM generation rely on left-to-right decoding without support for
backtracking, limiting the ability to correct or refine outputs mid-generation.
  To address this, we introduce IterGen, a user-friendly library for iterative,
grammar-guided LLM generation that enables users to move both forward and
backward within the generated output based on grammar symbols. By leveraging a
symbol-to-position mapping and maintaining the key-value (KV) cache state,
IterGen ensures efficient and structured generation while allowing for
corrections during the process. We demonstrate IterGen's effectiveness in two
important applications: reducing privacy leakage in LLM outputs and improving
the accuracy of LLM-generated SQL and Vega-Lite queries.
  Our code and additional resources are available at https://structuredllm.com.
