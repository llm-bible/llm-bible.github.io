---
layout: publication
title: 'A Layered Multi-expert Framework For Long-context Mental Health Assessments'
authors: Jinwen Tang, Qiming Guo, Wenbo Sun, Yi Shang
conference: "Arxiv"
year: 2025
bibkey: tang2025layered
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13951"}
tags: ['RAG', 'Tools', 'Reinforcement Learning']
---
Long-form mental health assessments pose unique challenges for large language
models (LLMs), which often exhibit hallucinations or inconsistent reasoning
when handling extended, domain-specific contexts. We introduce Stacked
Multi-Model Reasoning (SMMR), a layered framework that leverages multiple LLMs
and specialized smaller models as coequal 'experts'. Early layers isolate
short, discrete subtasks, while later layers integrate and refine these partial
outputs through more advanced long-context models. We evaluate SMMR on the
DAIC-WOZ depression-screening dataset and 48 curated case studies with
psychiatric diagnoses, demonstrating consistent improvements over single-model
baselines in terms of accuracy, F1-score, and PHQ-8 error reduction. By
harnessing diverse 'second opinions', SMMR mitigates hallucinations, captures
subtle clinical nuances, and enhances reliability in high-stakes mental health
assessments. Our findings underscore the value of multi-expert frameworks for
more trustworthy AI-driven screening.
