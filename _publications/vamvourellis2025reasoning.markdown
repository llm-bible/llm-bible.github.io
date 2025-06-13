---
layout: publication
title: 'Reasoning Or Overthinking: Evaluating Large Language Models On Financial Sentiment Analysis'
authors: Dimitris Vamvourellis, Dhagash Mehta
conference: "Arxiv"
year: 2025
bibkey: vamvourellis2025reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.04574'}
tags: ['GPT', 'BERT', 'Applications', 'Prompting', 'Model Architecture', 'Reinforcement Learning']
---
We investigate the effectiveness of large language models (LLMs), including reasoning-based and non-reasoning models, in performing zero-shot financial sentiment analysis. Using the Financial PhraseBank dataset annotated by domain experts, we evaluate how various LLMs and prompting strategies align with human-labeled sentiment in a financial context. We compare three proprietary LLMs (GPT-4o, GPT-4.1, o3-mini) under different prompting paradigms that simulate System 1 (fast and intuitive) or System 2 (slow and deliberate) thinking and benchmark them against two smaller models (FinBERT-Prosus, FinBERT-Tone) fine-tuned on financial sentiment analysis. Our findings suggest that reasoning, either through prompting or inherent model design, does not improve performance on this task. Surprisingly, the most accurate and human-aligned combination of model and method was GPT-4o without any Chain-of-Thought (CoT) prompting. We further explore how performance is impacted by linguistic complexity and annotation agreement levels, uncovering that reasoning may introduce overthinking, leading to suboptimal predictions. This suggests that for financial sentiment classification, fast, intuitive "System 1"-like thinking aligns more closely with human judgment compared to "System 2"-style slower, deliberative reasoning simulated by reasoning models or CoT prompting. Our results challenge the default assumption that more reasoning always leads to better LLM decisions, particularly in high-stakes financial applications.
