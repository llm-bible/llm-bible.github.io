---
layout: publication
title: 'Revisiting Verilogeval: A Year Of Improvements In Large-language Models For Hardware Code Generation'
authors: Nathaniel Pinckney, Christopher Batten, Mingjie Liu, Haoxing Ren, Brucek Khailany
conference: "Arxiv"
year: 2024
bibkey: pinckney2024revisiting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.11053'}
tags: ['GPT', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Prompting', 'Applications', 'Reinforcement Learning', 'In-Context Learning']
---
The application of large-language models (LLMs) to digital hardware code
generation is an emerging field, with most LLMs primarily trained on natural
language and software code. Hardware code like Verilog constitutes a small
portion of training data, and few hardware benchmarks exist. The open-source
VerilogEval benchmark, released in November 2023, provided a consistent
evaluation framework for LLMs on code completion tasks. Since then, both
commercial and open models have seen significant development.
  In this work, we evaluate new commercial and open models since VerilogEval's
original release-including GPT-4o, GPT-4 Turbo, Llama3.1 (8B/70B/405B), Llama3
70B, Mistral Large, DeepSeek Coder (33B and 6.7B), CodeGemma 7B, and
RTL-Coder-against an improved VerilogEval benchmark suite. We find measurable
improvements in state-of-the-art models: GPT-4o achieves a 63% pass rate on
specification-to-RTL tasks. The recently released and open Llama3.1 405B
achieves a 58% pass rate, almost matching GPT-4o, while the smaller
domain-specific RTL-Coder 6.7B models achieve an impressive 34% pass rate.
  Additionally, we enhance VerilogEval's infrastructure by automatically
classifying failures, introducing in-context learning support, and extending
the tasks to specification-to-RTL translation. We find that prompt engineering
remains crucial for achieving good pass rates and varies widely with model and
task. A benchmark infrastructure that allows for prompt engineering and failure
analysis is essential for continued model development and deployment.
