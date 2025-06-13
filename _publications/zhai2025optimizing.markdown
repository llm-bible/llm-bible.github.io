---
layout: publication
title: 'Excot: Optimizing Reasoning For Text-to-sql With Execution Feedback'
authors: Bohan Zhai, Canwen Xu, Yuxiong He, Zhewei Yao
conference: "Arxiv"
year: 2025
bibkey: zhai2025optimizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19988'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization', 'Tools']
---
Text-to-SQL demands precise reasoning to convert natural language questions
into structured queries. While large language models (LLMs) excel in many
reasoning tasks, their ability to leverage Chain-of-Thought (CoT) reasoning for
text-to-SQL remains underexplored. We identify critical limitations: zero-shot
CoT offers minimal gains, and Direct Preference Optimization (DPO) applied
without CoT yields marginal improvements. We propose ExCoT, a novel framework
that iteratively optimizes open-source LLMs by combining CoT reasoning with
off-policy and on-policy DPO, relying solely on execution accuracy as feedback.
This approach eliminates the need for reward models or human-annotated
preferences.
  Our experimental results demonstrate significant performance gains: ExCoT
improves execution accuracy on BIRD dev set from 57.37% to 68.51% and on Spider
test set from 78.81% to 86.59% for LLaMA-3 70B, with Qwen-2.5-Coder
demonstrating similar improvements. Our best model achieves state-of-the-art
performance in the single-model setting on both BIRD and Spider datasets,
notably achieving 68.53% on the BIRD test set.
