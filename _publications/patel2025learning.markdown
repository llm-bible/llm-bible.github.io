---
layout: publication
title: 'Learning API Functionality From Demonstrations For Tool-based Agents'
authors: Bhrij Patel, Ashish Jagmohan, Aditya Vempaty
conference: "Arxiv"
year: 2025
bibkey: patel2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24197'}
tags: ['Fine-Tuning', 'Agentic', 'Tools']
---
Digital tool-based agents that invoke external Application Programming Interfaces (APIs) often rely on documentation to understand API functionality. However, such documentation is frequently missing, outdated, privatized, or inconsistent-hindering the development of reliable, general-purpose agents. In this work, we propose learning API functionality directly from demonstrations as a new paradigm applicable in scenarios without documentation. Using existing API benchmarks, we collect demonstrations from both expert API-based agents and from self-exploration. To understand what information demonstrations must convey for successful task completion, we extensively study how the number of demonstrations and the use of LLM-generated summaries and evaluations affect the task success rate of the API-based agent. Our experiments across 3 datasets and 5 models show that learning functionality from demonstrations remains a non-trivial challenge, even for state-of-the-art LLMs. We find that providing explicit function calls and natural language critiques significantly improves the agent's task success rate due to more accurate parameter filling. We analyze failure modes, identify sources of error, and highlight key open challenges for future work in documentation-free, self-improving, API-based agents.
