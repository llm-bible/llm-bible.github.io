---
layout: publication
title: 'Leveraging Prior Experience: An Expandable Auxiliary Knowledge Base For Text-to-sql'
authors: Zhibo Chu, Zichong Wang, Qitao Qin
conference: "Arxiv"
year: 2024
bibkey: chu2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13244"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Large Language Models (LLMs) exhibit impressive problem-solving skills across
many tasks, but they still underperform compared to humans in various
downstream applications, such as text-to-SQL. On the BIRD benchmark
leaderboard, human performance achieves an accuracy of 92.96%, whereas the
top-performing method reaches only 72.39%. Notably, these state-of-the-art
(SoTA) methods predominantly rely on in-context learning to simulate human-like
reasoning. However, they overlook a critical human skill: continual learning.
Inspired by the educational practice of maintaining mistake notebooks during
our formative years, we propose LPE-SQL (Leveraging Prior Experience: An
Expandable Auxiliary Knowledge Base for Text-to-SQL), a novel framework
designed to augment LLMs by enabling continual learning without requiring
parameter fine-tuning. LPE-SQL consists of four modules that \textbf\{i)\}
retrieve relevant entries, \textbf\{ii)\} efficient sql generation, \textbf\{iii)\}
generate the final result through a cross-consistency mechanism and
\textbf\{iv)\} log successful and failed tasks along with their reasoning
processes or reflection-generated tips. Importantly, the core module of LPE-SQL
is the fourth one, while the other modules employ foundational methods,
allowing LPE-SQL to be easily integrated with SoTA technologies to further
enhance performance. Our experimental results demonstrate that this continual
learning approach yields substantial performance gains, with the smaller
Llama-3.1-70B model with surpassing the performance of the larger
Llama-3.1-405B model using SoTA methods.
