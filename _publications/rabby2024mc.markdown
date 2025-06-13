---
layout: publication
title: 'MC-NEST: Enhancing Mathematical Reasoning In Large Language Models Leveraging A Monte Carlo Self-refine Tree'
authors: Gollam Rabby, Farhana Keya, Sören Auer
conference: "Arxiv"
year: 2024
bibkey: rabby2024mc
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.15645'}
tags: ['RAG', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Reinforcement Learning']
---
Mathematical reasoning presents significant challenges for large language models (LLMs). To enhance their capabilities, we propose Monte Carlo Self-Refine Tree (MC-NEST), an extension of Monte Carlo Tree Search that integrates LLM-based self-refinement and self-evaluation for improved decision-making in complex reasoning tasks. MC-NEST balances exploration and exploitation using Upper Confidence Bound (UCT) scores combined with diverse selection policies. Through iterative critique and refinement, LLMs learn to reason more strategically. Empirical results demonstrate that MC-NEST with an importance sampling policy substantially improves GPT-4o's performance, achieving state-of-the-art pass@1 scores on Olympiad-level benchmarks. Specifically, MC-NEST attains a pass@1 of 38.6 on AIME and 12.6 on MathOdyssey. The solution quality for MC-NEST using GPT-4o and Phi-3-mini reaches 84.0% and 82.08%, respectively, indicating robust consistency across different LLMs. MC-NEST performs strongly across Algebra, Geometry, and Number Theory, benefiting from its ability to handle abstraction, logical deduction, and multi-step reasoning -- core skills in mathematical problem solving.
