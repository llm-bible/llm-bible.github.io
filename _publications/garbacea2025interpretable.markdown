---
layout: publication
title: 'Hyperalign: Interpretable Personalized LLM Alignment Via Hypothesis Generation'
authors: Cristina Garbacea, Chenhao Tan
conference: "Arxiv"
year: 2025
bibkey: garbacea2025interpretable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00038'}
tags: ['Few-Shot', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Alignment algorithms are widely used to align large language models (LLMs) to human users based on preference annotations. Typically these (often divergent) preferences are aggregated over a diverse set of users, resulting in fine-tuned models that are aligned to the ``average-user'' preference. Nevertheless, current models are used by individual users in very specific contexts and situations, emphasizing the need for user-dependent preference control. In this work we address the problem of personalizing LLM outputs to their users. We aim to generate customized responses tailored to specific individuals instead of generic outputs that emulate the collective voices of diverse populations. We propose HyPerAlign, an interpretable and sample-efficient hypothesis-driven personalization approach for LLM models. Given few-shot examples written by a particular user, we first infer hypotheses about their communication strategies, personality, and writing style, then prompt LLM models with these hypotheses and user-specific attributes to generate customized outputs. We conduct experiments on two different personalization tasks, namely authorship attribution and deliberative alignment, with datasets from diverse domains (news articles, blog posts, emails, jailbreaking benchmarks). Results demonstrate the superiority of hypothesis-driven LLM personalization compared to preference-based fine-tuning methods. For authorship attribution, HyPerAlign generations have consistently high win-rates (commonly \\(> 90%\\)) against state-of-the-art preference fine-tuning approaches across diverse user profiles and LLM models. For deliberative alignment, the helpfulness of LLM models is improved by up to \\(70%\\) on average. Overall, HyPerAlign represents an interpretable and sample-efficient strategy for the personalization of LLM models to individual users.
