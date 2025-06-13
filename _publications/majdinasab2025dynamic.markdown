---
layout: publication
title: 'Prism: Dynamic And Flexible Benchmarking Of Llms Code Generation With Monte Carlo Tree Search'
authors: Vahid Majdinasab, Amin Nikanjam, Foutse Khomh
conference: "Arxiv"
year: 2025
bibkey: majdinasab2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05500"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Applications']
---
The rapid advancement of Large Language Models (LLMs) has outpaced
traditional evaluation methods. Static benchmarks fail to capture the depth and
breadth of LLM capabilities and eventually become obsolete, while most dynamic
approaches either rely too heavily on LLM-based evaluation or remain
constrained by predefined test sets. We introduce Prism, a flexible, dynamic
benchmarking framework designed for comprehensive LLM assessment. Prism builds
on three key components: (1) a tree-based state representation that models
evaluation as a Markov Decision Process, (2) a Monte Carlo Tree Search
algorithm adapted to uncover challenging evaluation scenarios, and (3) a
multi-agent evaluation pipeline that enables simultaneous assessment of diverse
capabilities. To ensure robust evaluation, Prism integrates structural
measurements of tree exploration patterns with performance metrics across
difficulty levels, providing detailed diagnostics of error patterns, test
coverage, and solution approaches. Through extensive experiments on five
state-of-the-art LLMs, we analyze how model architecture and scale influence
code generation performance across varying task difficulties. Our results
demonstrate Prism's effectiveness as a dynamic benchmark that evolves with
model advancements while offering deeper insights into their limitations.
