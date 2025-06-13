---
layout: publication
title: 'Llm-first Search: Self-guided Exploration Of The Solution Space'
authors: Nathan Herr, Tim Rocktäschel, Roberta Raileanu
conference: "Arxiv"
year: 2025
bibkey: herr2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.05213"}
  - {name: "Code", url: "https://github.com/NathanHerr/LLM-First-Search}{LLM-First-Search"}
tags: ['Fine-Tuning', 'Has Code', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated remarkable improvements in reasoning and planning through increased test-time compute, often by framing problem-solving as a search process. While methods like Monte Carlo Tree Search (MCTS) have proven effective in some domains, their reliance on fixed exploration hyperparameters limits their adaptability across tasks of varying difficulty, rendering them impractical or expensive in certain settings. In this paper, we propose \textbf\{LLM-First Search (LFS)\}, a novel \textit\{LLM Self-Guided Search\} method that removes the need for pre-defined search strategies by empowering the LLM to autonomously control the search process via self-guided exploration. Rather than relying on external heuristics or hardcoded policies, the LLM evaluates whether to pursue the current search path or explore alternative branches based on its internal scoring mechanisms. This enables more flexible and context-sensitive reasoning without requiring manual tuning or task-specific adaptation. We evaluate LFS on Countdown and Sudoku against three classic widely-used search algorithms, Tree-of-Thoughts' Breadth First Search (ToT-BFS), Best First Search (BestFS), and MCTS, each of which have been used to achieve SotA results on a range of challenging reasoning tasks. We found that LFS (1) performs better on more challenging tasks without additional tuning, (2) is more computationally efficient compared to the other methods, especially when powered by a stronger model, (3) scales better with stronger models, due to its LLM-First design, and (4) scales better with increased compute budget. Our code is publicly available at \href\{https://github.com/NathanHerr/LLM-First-Search\}\{LLM-First-Search\}.
