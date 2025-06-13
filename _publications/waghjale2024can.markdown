---
layout: publication
title: 'ECCO: Can We Improve Model-generated Code Efficiency Without Sacrificing Functional Correctness?'
authors: Siddhant Waghjale, Vishruth Veerendranath, Zora Zhiruo Wang, Daniel Fried
conference: "Arxiv"
year: 2024
bibkey: waghjale2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14044"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Although large language models (LLMs) have been largely successful in
generating functionally correct programs, conditioning models to produce
efficient solutions while ensuring correctness remains a challenge. Further,
unreliability in benchmarking code efficiency is a hurdle across varying
hardware specifications for popular interpreted languages such as Python. In
this paper, we present ECCO, a reproducible benchmark for evaluating program
efficiency via two paradigms: natural language (NL) based code generation and
history-based code editing. On ECCO, we adapt and thoroughly investigate the
three most promising existing LLM-based approaches: in-context learning,
iterative refinement with execution or NL feedback, and fine-tuning conditioned
on execution and editing history. While most methods degrade functional
correctness and moderately increase program efficiency, we find that adding
execution information often helps maintain functional correctness, and NL
feedback enhances more on efficiency. We release our benchmark to support
future work on LLM-based generation of efficient code.
