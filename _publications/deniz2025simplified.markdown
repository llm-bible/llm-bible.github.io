---
layout: publication
title: 'Aixamine: Simplified LLM Safety And Security'
authors: Fatih Deniz, Dorde Popovic, Yazan Boshmaf, Euisuh Jeong, Minhaj Ahmad, Sanjay Chawla, Issa Khalil
conference: "Arxiv"
year: 2025
bibkey: deniz2025simplified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14985"}
tags: ['Responsible AI', 'Tools', 'GPT', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Bias Mitigation', 'Model Architecture', 'Security', 'Training Techniques', 'Fairness', 'Distillation']
---
Evaluating Large Language Models (LLMs) for safety and security remains a
complex task, often requiring users to navigate a fragmented landscape of ad
hoc benchmarks, datasets, metrics, and reporting formats. To address this
challenge, we present aiXamine, a comprehensive black-box evaluation platform
for LLM safety and security. aiXamine integrates over 40 tests (i.e.,
benchmarks) organized into eight key services targeting specific dimensions of
safety and security: adversarial robustness, code security, fairness and bias,
hallucination, model and data privacy, out-of-distribution (OOD) robustness,
over-refusal, and safety alignment. The platform aggregates the evaluation
results into a single detailed report per model, providing a detailed breakdown
of model performance, test examples, and rich visualizations. We used aiXamine
to assess over 50 publicly available and proprietary LLMs, conducting over 2K
examinations. Our findings reveal notable vulnerabilities in leading models,
including susceptibility to adversarial attacks in OpenAI's GPT-4o, biased
outputs in xAI's Grok-3, and privacy weaknesses in Google's Gemini 2.0.
Additionally, we observe that open-source models can match or exceed
proprietary models in specific services such as safety alignment, fairness and
bias, and OOD robustness. Finally, we identify trade-offs between distillation
strategies, model size, training methods, and architectural choices.
