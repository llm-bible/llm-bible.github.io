---
layout: publication
title: 'Making Large Language Models Better Reasoners With Alignment'
authors: Peiyi Wang, Lei Li, Liang Chen, Feifan Song, Binghuai Lin, Yunbo Cao, Tianyu Liu, Zhifang Sui
conference: "Arxiv"
year: 2023
bibkey: wang2023making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02144"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Reasoning is a cognitive process of using evidence to reach a sound
conclusion. The reasoning capability is essential for large language models
(LLMs) to serve as the brain of the artificial general intelligence agent.
Recent studies reveal that fine-tuning LLMs on data with the chain of thought
(COT) reasoning process can significantly enhance their reasoning capabilities.
However, we find that the fine-tuned LLMs suffer from an \textit\{Assessment
Misalignment\} problem, i.e., they frequently assign higher scores to subpar
COTs, leading to potential limitations in their reasoning abilities. To address
this problem, we introduce an \textit\{Alignment Fine-Tuning (AFT)\} paradigm,
which involves three steps: 1) fine-tuning LLMs with COT training data; 2)
generating multiple COT responses for each question, and categorizing them into
positive and negative ones based on whether they achieve the correct answer; 3)
calibrating the scores of positive and negative responses given by LLMs with a
novel constraint alignment loss. Specifically, the constraint alignment loss
has two objectives: a) Alignment, which guarantees that positive scores surpass
negative scores to encourage answers with high-quality COTs; b) Constraint,
which keeps the negative scores confined to a reasonable range to prevent the
model degradation. Beyond just the binary positive and negative feedback, the
constraint alignment loss can be seamlessly adapted to the ranking situations
when ranking feedback is accessible. Furthermore, we also delve deeply into
recent ranking-based alignment methods, such as DPO, RRHF, and PRO, and
discover that the constraint, which has been overlooked by these approaches, is
also crucial for their performance. Extensive experiments on four reasoning
benchmarks with both binary and ranking feedback demonstrate the effectiveness
of AFT.
