---
layout: publication
title: 'Tree Of Problems: Improving Structured Problem Solving With Compositionality'
authors: Armel Zebaze, Benoît Sagot, Rachel Bawden
conference: "Arxiv"
year: 2024
bibkey: zebaze2024tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06634"}
  - {name: "Code", url: "https://github.com/ArmelRandy/tree-of-problems"}
tags: ['Prompting', 'Has Code', 'In-Context Learning', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated remarkable performance across
multiple tasks through in-context learning. For complex reasoning tasks that
require step-by-step thinking, Chain-of-Thought (CoT) prompting has given
impressive results, especially when combined with self-consistency.
Nonetheless, some tasks remain particularly difficult for LLMs to solve. Tree
of Thoughts (ToT) and Graph of Thoughts (GoT) emerged as alternatives, dividing
the complex problem into paths of subproblems. In this paper, we propose Tree
of Problems (ToP), a simpler version of ToT, which we hypothesise can work
better for complex tasks that can be divided into identical subtasks. Our
empirical results show that our approach outperforms ToT and GoT, and in
addition performs better than CoT on complex reasoning tasks. All code for this
paper is publicly available here:
https://github.com/ArmelRandy/tree-of-problems.
