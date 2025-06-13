---
layout: publication
title: 'LLM4VV: Developing Llm-driven Testsuite For Compiler Validation'
authors: Christian Munley, Aaron Jarmusch, Sunita Chandrasekaran
conference: "Arxiv"
year: 2023
bibkey: munley2023developing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04963"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) are a new and powerful tool for a wide span of
applications involving natural language and demonstrate impressive code
generation abilities. The goal of this work is to automatically generate tests
and use these tests to validate and verify compiler implementations of a
directive-based parallel programming paradigm, OpenACC. To do so, in this
paper, we explore the capabilities of state-of-the-art LLMs, including
open-source LLMs -- Meta Codellama, Phind fine-tuned version of Codellama,
Deepseek Deepseek Coder and closed-source LLMs -- OpenAI GPT-3.5-Turbo and
GPT-4-Turbo. We further fine-tuned the open-source LLMs and GPT-3.5-Turbo using
our own testsuite dataset along with using the OpenACC specification. We also
explored these LLMs using various prompt engineering techniques that include
code template, template with retrieval-augmented generation (RAG), one-shot
example, one-shot with RAG, expressive prompt with code template and RAG. This
paper highlights our findings from over 5000 tests generated via all the above
mentioned methods. Our contributions include: (a) exploring the capabilities of
the latest and relevant LLMs for code generation, (b) investigating fine-tuning
and prompt methods, and (c) analyzing the outcome of LLMs generated tests
including manually analysis of representative set of tests. We found the LLM
Deepseek-Coder-33b-Instruct produced the most passing tests followed by
GPT-4-Turbo.
