---
layout: publication
title: 'CHORUS: Zero-shot Hierarchical Retrieval And Orchestration For Generating Linear Programming Code'
authors: Tasnim Ahmed, Salimur Choudhury
conference: "Arxiv"
year: 2025
bibkey: ahmed2025zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01485'}
tags: ['RAG', 'Efficiency and Optimization', 'Model Architecture', 'GPT', 'Tools', 'Prompting', 'Applications']
---
Linear Programming (LP) problems aim to find the optimal solution to an
objective under constraints. These problems typically require domain knowledge,
mathematical skills, and programming ability, presenting significant challenges
for non-experts. This study explores the efficiency of Large Language Models
(LLMs) in generating solver-specific LP code. We propose CHORUS, a
retrieval-augmented generation (RAG) framework for synthesizing Gurobi-based LP
code from natural language problem statements. CHORUS incorporates a
hierarchical tree-like chunking strategy for theoretical contents and generates
additional metadata based on code examples from documentation to facilitate
self-contained, semantically coherent retrieval. Two-stage retrieval approach
of CHORUS followed by cross-encoder reranking further ensures contextual
relevance. Finally, expertly crafted prompt and structured parser with
reasoning steps improve code generation performance significantly. Experiments
on the NL4Opt-Code benchmark show that CHORUS improves the performance of
open-source LLMs such as Llama3.1 (8B), Llama3.3 (70B), Phi4 (14B), Deepseek-r1
(32B), and Qwen2.5-coder (32B) by a significant margin compared to baseline and
conventional RAG. It also allows these open-source LLMs to outperform or match
the performance of much stronger baselines-GPT3.5 and GPT4 while requiring far
fewer computational resources. Ablation studies further demonstrate the
importance of expert prompting, hierarchical chunking, and structured
reasoning.
