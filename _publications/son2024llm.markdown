---
layout: publication
title: 'Llm-as-a-judge & Reward Model: What They Can And Cannot Do'
authors: Guijin Son, Hyunwoo Ko, Hoyoung Lee, Yewon Kim, Seunghyeok Hong
conference: "Arxiv"
year: 2024
bibkey: son2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11239"}
tags: ['Agentic', 'Prompting', 'Reinforcement Learning']
---
LLM-as-a-Judge and reward models are widely used alternatives of
multiple-choice questions or human annotators for large language model (LLM)
evaluation. Their efficacy shines in evaluating long-form responses, serving a
critical role as evaluators of leaderboards and as proxies to align LLMs via
reinforcement learning. However, despite their popularity, their effectiveness
in diverse contexts, such as non-English prompts, factual verification, or
challenging questions, remains unexplored. In this paper, we conduct a
comprehensive analysis of automated evaluators, reporting several key findings
on their behavior. First, we discover that English evaluation capabilities
significantly influence language-specific evaluation capabilities, often more
than the language proficiency itself, enabling evaluators trained in English to
easily transfer their skills to other languages. Second, we identify critical
shortcomings, where LLMs fail to detect and penalize errors, such as factual
inaccuracies, cultural misrepresentations, and the presence of unwanted
language. Finally, we find that state-of-the-art evaluators struggle with
challenging prompts, in either English or Korean, underscoring their
limitations in assessing or generating complex reasoning questions. We release
the dataset and codes used.
