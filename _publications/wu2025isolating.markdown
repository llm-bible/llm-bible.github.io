---
layout: publication
title: 'Isolating Language-coding From Problem-solving: Benchmarking Llms With Pseudoeval'
authors: Jiarong Wu, Songqiang Chen, Jialun Cao, Hau Ching Lo, Shing-chi Cheung
conference: "Arxiv"
year: 2025
bibkey: wu2025isolating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19149"}
  - {name: "Code", url: "https://anonymous.4open.science/r/PseudocodeACL25-7B74"}
tags: ['Has Code', 'Applications', 'EACL', 'ACL']
---
Existing code generation benchmarks for Large Language Models (LLMs) such as
HumanEval and MBPP are designed to study LLMs' end-to-end performance, where
the benchmarks feed a problem description in natural language as input and
examine the generated code in specific programming languages. However, the
evaluation scores revealed in this way provide a little hint as to the
bottleneck of the code generation -- whether LLMs are struggling with their
problem-solving capability or language-coding capability. To answer this
question, we construct PseudoEval, a multilingual code generation benchmark
that provides a solution written in pseudocode as input. By doing so, the
bottleneck of code generation in various programming languages could be
isolated and identified. Our study yields several interesting findings. For
example, we identify that the bottleneck of LLMs in Python programming is
problem-solving, while Rust is struggling relatively more in language-coding.
Also, our study indicates that problem-solving capability may transfer across
programming languages, while language-coding needs more language-specific
effort, especially for undertrained programming languages. Finally, we release
the pipeline of constructing PseudoEval to facilitate the extension to existing
benchmarks. PseudoEval is available at:
https://anonymous.4open.science/r/PseudocodeACL25-7B74.
