---
layout: publication
title: 'Comat: Chain Of Mathematically Annotated Thought Improves Mathematical Reasoning'
authors: Joshua Ong Jun Leang, Aryo Pradipta Gema, Shay B. Cohen
conference: "Arxiv"
year: 2024
bibkey: leang2024chain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10336'}
tags: ['Prompting']
---
Mathematical reasoning remains a significant challenge for large language
models (LLMs), despite progress in prompting techniques such as
Chain-of-Thought (CoT). We present Chain of Mathematically Annotated Thought
(CoMAT), which enhances reasoning through two stages: Symbolic Conversion
(converting natural language queries into symbolic form) and Reasoning
Execution (deriving answers from symbolic representations). CoMAT operates
entirely with a single LLM and without external solvers. Across four LLMs,
CoMAT outperforms traditional CoT on six out of seven benchmarks, achieving
gains of 4.48% on MMLU-Redux (MATH) and 4.58% on GaoKao MCQ. In addition to
improved performance, CoMAT ensures faithfulness and verifiability, offering a
transparent reasoning process for complex mathematical tasks
