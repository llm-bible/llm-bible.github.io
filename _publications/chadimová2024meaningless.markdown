---
layout: publication
title: 'Meaningless Is Better: Hashing Bias-inducing Words In LLM Prompts Improves Performance In Logical Reasoning And Statistical Learning'
authors: Milena Chadimová, Eduard Jurášek, Tomáš Kliegr
conference: "Arxiv"
year: 2024
bibkey: chadimová2024meaningless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17304"}
tags: ['Prompting', 'Ethics and Bias', 'Model Architecture', 'GPT']
---
This paper introduces a novel method, referred to as "hashing", which
involves masking potentially bias-inducing words in large language models
(LLMs) with hash-like meaningless identifiers to reduce cognitive biases and
reliance on external knowledge. The method was tested across three sets of
experiments involving a total of 490 prompts. Statistical analysis using
chi-square tests showed significant improvements in all tested scenarios, which
covered LLama, ChatGPT, Copilot, Gemini and Mixtral models. In the first
experiment, hashing decreased the fallacy rate in a modified version of the
"Linda" problem aimed at evaluating susceptibility to cognitive biases. In the
second experiment, it improved LLM results on the frequent itemset extraction
task. In the third experiment, we found hashing is also effective when the
Linda problem is presented in a tabular format rather than text, indicating
that the technique works across various input representations. Overall, the
method was shown to improve bias reduction and incorporation of external
knowledge. Despite bias reduction, hallucination rates were inconsistently
reduced across types of LLM models. These findings suggest that masking
bias-inducing terms can improve LLM performance, although its effectiveness is
model- and task-dependent.
