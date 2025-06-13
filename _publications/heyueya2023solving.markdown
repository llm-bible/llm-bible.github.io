---
layout: publication
title: 'Solving Math Word Problems By Combining Language Models With Symbolic Solvers'
authors: Joy He-yueya, Gabriel Poesia, Rose E. Wang, Noah D. Goodman
conference: "Arxiv"
year: 2023
bibkey: heyueya2023solving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.09102"}
  - {name: "Code", url: "https://github.com/joyheyueya/declarative-math-word-problem"}
tags: ['Tools', 'Ethics and Bias', 'Applications', 'Has Code', 'Prompting']
---
Automatically generating high-quality step-by-step solutions to math word
problems has many applications in education. Recently, combining large language
models (LLMs) with external tools to perform complex reasoning and calculation
has emerged as a promising direction for solving math word problems, but prior
approaches such as Program-Aided Language model (PAL) are biased towards simple
procedural problems and less effective for problems that require declarative
reasoning. We propose an approach that combines an LLM that can incrementally
formalize word problems as a set of variables and equations with an external
symbolic solver that can solve the equations. Our approach achieves comparable
accuracy to the original PAL on the GSM8K benchmark of math word problems and
outperforms PAL by an absolute 20% on ALGEBRA, a new dataset of more
challenging word problems extracted from Algebra textbooks. Our work highlights
the benefits of using declarative and incremental representations when
interfacing with an external tool for solving complex math word problems. Our
data and prompts are publicly available at
https://github.com/joyheyueya/declarative-math-word-problem.
