---
layout: publication
title: 'Humaneval Pro And MBPP Pro: Evaluating Large Language Models On Self-invoking Code Generation'
authors: Zhaojian Yu, Yilun Zhao, Arman Cohan, Xiao-ping Zhang
conference: "Arxiv"
year: 2024
bibkey: yu2024humaneval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.21199"}
tags: ['Applications']
---
We introduce self-invoking code generation, a new task designed to evaluate
the progressive reasoning and problem-solving capabilities of LLMs. In this
task, models are presented with a base problem and a related, more complex
problem. They must solve the base problem and then utilize its solution to
address the more complex one. This work features three key contributions.
First, we propose a general recipe for generating more challenging versions of
existing benchmarks, resulting in three new benchmarks: HumanEval Pro, MBPP
Pro, and BigCodeBench-Lite Pro, specifically designed to assess LLMs on
self-invoking code generation. Second, from the analysis of experimental
results over twenty LLMs on our benchmarks, we have two important observations:
(i) Most LLMs excel in traditional code generation benchmarks like HumanEval
and MBPP, but their performance declines on self-invoking tasks. For example,
o1-mini achieves 96.2% pass@1 on HumanEval but only 76.2% on HumanEval Pro.
(ii) On self-invoking code generation task, the instruction-tuned models
demonstrate only marginal improvements compared to the base models. Third, we
disclose the types of failure modes that exist in our evaluation results. All
these results underscore the need for further advancements in self-invoking
code generation tasks and provide a new direction for future research on
enhancing LLMs' code reasoning capabilities.
