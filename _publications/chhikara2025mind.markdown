---
layout: publication
title: 'Mind The Confidence Gap: Overconfidence, Calibration, And Distractor Effects In Large Language Models'
authors: Prateek Chhikara
conference: "Arxiv"
year: 2025
bibkey: chhikara2025mind
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11028'}
tags: ['Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) show remarkable proficiency in natural language tasks, yet their frequent overconfidence-misalignment between predicted confidence and true correctness-poses significant risks in critical decision-making applications. We present a comprehensive analysis on calibration in LLMs across nine LLMs and three factual Question-Answering (QA) datasets, systematically comparing standard free-generation settings against structured distractor-augmented prompts. Our evaluation reveals that explicitly incorporating distractors can substantially mitigate miscalibration, achieving relative accuracy improvements up to 460% and ECE reductions up to 90%. Despite general trends, we uncover nuanced findings: large RLHF-tuned models display inherent calibration strengths but can paradoxically suffer increased miscalibration on easier queries, whereas smaller models benefit disproportionately from distractor prompts but remain significantly miscalibrated. Through detailed analyses across question types, we identify persistent calibration failures, particularly in person-based queries. We conclude with concrete recommendations-targeted fine-tuning, structured prompting, and strategic model choice-to ensure reliable, trustworthy LLM deployments.
