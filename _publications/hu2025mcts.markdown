---
layout: publication
title: 'MCTS-RAG: Enhancing Retrieval-augmented Generation With Monte Carlo Tree Search'
authors: Yunhai Hu, Yilun Zhao, Chen Zhao, Arman Cohan
conference: "Arxiv"
year: 2025
bibkey: hu2025mcts
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.20757'}
tags: ['Reinforcement Learning', 'RAG', 'GPT', 'Model Architecture']
---
We introduce MCTS-RAG, a novel approach that enhances the reasoning
capabilities of small language models on knowledge-intensive tasks by
leveraging retrieval-augmented generation (RAG) to provide relevant context and
Monte Carlo Tree Search (MCTS) to refine reasoning paths. MCTS-RAG dynamically
integrates retrieval and reasoning through an iterative decision-making
process. Unlike standard RAG methods, which typically retrieve information
independently from reasoning and thus integrate knowledge suboptimally, or
conventional MCTS reasoning, which depends solely on internal model knowledge
without external facts, MCTS-RAG combines structured reasoning with adaptive
retrieval. This integrated approach enhances decision-making, reduces
hallucinations, and ensures improved factual accuracy and response consistency.
The experimental results on multiple reasoning and knowledge-intensive datasets
datasets (i.e., ComplexWebQA, GPQA, and FoolMeTwice) show that our method
enables small-scale LMs to achieve performance comparable to frontier LLMs like
GPT-4o by effectively scaling inference-time compute, setting a new standard
for reasoning in small-scale models.
