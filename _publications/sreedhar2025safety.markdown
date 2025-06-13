---
layout: publication
title: 'Safety Through Reasoning: An Empirical Study Of Reasoning Guardrail Models'
authors: Makesh Narsimhan Sreedhar, Traian Rebedea, Christopher Parisien
conference: "Arxiv"
year: 2025
bibkey: sreedhar2025safety
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20087'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Reinforcement Learning', 'Responsible AI']
---
Reasoning-based language models have demonstrated strong performance across various domains, with the most notable gains seen in mathematical and coding tasks. Recent research has shown that reasoning also offers significant benefits for LLM safety and guardrail applications. In this work, we conduct a comprehensive analysis of training reasoning-based guardrail models for content moderation, with an emphasis on generalization to custom safety policies at inference time. Our study focuses on two key dimensions: data efficiency and inference efficiency. On the data front, we find that reasoning-based models exhibit strong sample efficiency, achieving competitive performance with significantly fewer training examples than their non-reasoning counterparts. This unlocks the potential to repurpose the remaining data for mining high-value, difficult samples that further enhance model performance. On the inference side, we evaluate practical trade-offs by introducing reasoning budgets, examining the impact of reasoning length on latency and accuracy, and exploring dual-mode training to allow runtime control over reasoning behavior. Our findings will provide practical insights for researchers and developers to effectively and efficiently train and deploy reasoning-based guardrails models in real-world systems.
