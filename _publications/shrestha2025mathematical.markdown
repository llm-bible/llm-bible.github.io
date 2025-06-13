---
layout: publication
title: 'Mathematical Reasoning In Large Language Models: Assessing Logical And Arithmetic Errors Across Wide Numerical Ranges'
authors: Safal Shrestha, Minwu Kim, Keith Ross
conference: "Arxiv"
year: 2025
bibkey: shrestha2025mathematical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08680"}
tags: ['Security', 'Reinforcement Learning']
---
Mathematical reasoning in Large Language Models (LLMs) is often evaluated
using benchmarks with limited numerical ranges, failing to reflect real-world
problem-solving across diverse scales. Furthermore, most existing evaluation
methods only compare model outputs to ground-truth answers, obscuring insights
into reasoning processes. To address these limitations, we introduce
GSM-Ranges, a dataset generator derived from GSM8K that systematically perturbs
numerical values in math problems to assess model robustness across varying
numerical scales. Additionally, we propose a novel grading methodology that
distinguishes between logical and non-logical errors, offering a more precise
evaluation of reasoning processes beyond computational accuracy. Our
experiments with various models reveal a significant increase in logical error
rates-up to 14 percentage points-as numerical complexity rises, demonstrating a
general weakness in reasoning with out-of-distribution numerical values.
Moreover, while models demonstrate high accuracy on standalone arithmetic
tasks, their performance deteriorates substantially when computations are
embedded within word problems. These findings provide a comprehensive
evaluation of LLMs' mathematical reasoning capabilities and inform future
research directions for improving numerical generalization in language models.
