---
layout: publication
title: 'Weaker Llms'' Opinions Also Matter: Mixture Of Opinions Enhances Llm''s Mathematical Reasoning'
authors: Yanan Chen, Ali Pesaranghader, Tanmana Sadhu
conference: "Arxiv"
year: 2025
bibkey: chen2025weaker
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19622"}
tags: ['Agentic', 'Model Architecture', 'Training Techniques', 'Few-Shot', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Recent advances in Large Language Models (LLMs) have raised interest in their
formal reasoning capabilities, particularly in mathematics. While closed LLMs
like GPT-4 perform well on mathematical benchmarks, e.g., GSM8K, it remains
unclear whether small to medium-sized open LLMs can achieve similar
performance, questioning their reliability. To close this gap, we propose a
post-training approach leveraging a mixture of opinions (MoO) from weaker
ancillary LLMs to enhance a (relatively) stronger LLM's reasoning. For that,
each post-training sample is augmented with Chain-of-Thought (CoT) reasoning
steps and answers from ancillary LLMs, enabling the main LLM to learn from
diverse perspectives. We compare MoO with standard supervised fine-tuning
(SFT), few-shot prompting, and the Mixture of Agents (MoA) method on
mathematical reasoning benchmarks. Our results show that incorporating weaker
LLMs' opinions improves mathematical reasoning by an average of 5%,
highlighting the value of diverse perspectives in reasoning tasks.
