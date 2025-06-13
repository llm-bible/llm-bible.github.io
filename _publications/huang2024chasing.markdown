---
layout: publication
title: 'Chasing Progress, Not Perfection: Revisiting Strategies For End-to-end LLM Plan Generation'
authors: Sukai Huang, Trevor Cohn, Nir Lipovetzky
conference: "Arxiv"
year: 2024
bibkey: huang2024chasing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10675"}
tags: ['Fine-Tuning', 'Agentic', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
The capability of Large Language Models (LLMs) to plan remains a topic of
debate. Some critics argue that strategies to boost LLMs' reasoning skills are
ineffective in planning tasks, while others report strong outcomes merely from
training models on a planning corpus. This study reassesses recent strategies
by developing an end-to-end LLM planner and employing diverse metrics for a
thorough evaluation. We find that merely fine-tuning LLMs on a corpus of
planning instances does not lead to robust planning skills, as indicated by
poor performance on out-of-distribution test sets. At the same time, we find
that various strategies, including Chain-of-Thought, do enhance the probability
of a plan being executable. This indicates progress towards better plan
quality, despite not directly enhancing the final validity rate. Among the
strategies we evaluated, reinforcement learning with our novel `Longest
Contiguous Common Subsequence' reward emerged as the most effective,
contributing to both plan validity and executability. Overall, our research
addresses key misconceptions in the LLM-planning literature; we validate
incremental progress in plan executability, although plan validity remains a
challenge. Hence, future strategies should focus on both these aspects, drawing
insights from our findings.
