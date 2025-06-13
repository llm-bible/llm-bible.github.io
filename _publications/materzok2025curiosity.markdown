---
layout: publication
title: 'COS(M+O)S: Curiosity And Rl-enhanced MCTS For Exploring Story Space Via Language Models'
authors: Tobias Materzok
conference: "Arxiv"
year: 2025
bibkey: materzok2025curiosity
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.17104'}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'GPT', 'Prompting', 'Reinforcement Learning']
---
We present COS(M+O)S, a System 2-inspired framework for open-ended plot
development that systematically explores the vast space of possible story
expansions, enabling a 3B-parameter language model to approach the plot quality
of a 70B model on select short-story tasks. The method accomplishes this by
combining Monte Carlo Tree Search (MCTS), guided by a step-level value model
that rewards moderate surprisal (curiosity) while penalizing incoherence, and
Odds Ratio Preference Optimization (ORPO) to fine-tune the policy on high-value
plot expansions. This iterative reinforcement learning loop systematically
explores multiple candidate plot branches, backpropagates quality signals, and
adapts the policy for faster convergence, notably shifting the policy from
puzzle-based Chain-of-Thought to more character-driven storytelling. In
small-scale tests with short-story prompts, 67%-77% of participants favored
COS(M+O)S's highest-rated expansions over lower-rated ones, suggesting that our
learned value function aligns. GPT-4o ratings further show that COS(M+O)S
surpasses naive single-pass decoding from Llama 3.2 3B by 0.59 SD, coming
within 0.06 SD of Llama 3.1 70B (no significant difference, p=0.93). Pairwise
comparisons with o1 place COS(M+O)S 1.5 SD above the 3B baseline and find no
statistically significant gap from 70B. Nevertheless, absolute story quality
remains modest, constrained by the small model's capacity and limited training
data.
