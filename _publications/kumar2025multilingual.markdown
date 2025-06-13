---
layout: publication
title: 'Polyguard: A Multilingual Safety Moderation Tool For 17 Languages'
authors: Priyanshu Kumar, Devansh Jain, Akhila Yerukola, Liwei Jiang, Himanshu Beniwal, Thomas Hartvigsen, Maarten Sap
conference: "Arxiv"
year: 2025
bibkey: kumar2025multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04377'}
tags: ['Applications', 'Prompting', 'Responsible AI', 'Training Techniques']
---
Truly multilingual safety moderation efforts for Large Language Models (LLMs)
have been hindered by a narrow focus on a small set of languages (e.g.,
English, Chinese) as well as a limited scope of safety definition, resulting in
significant gaps in moderation capabilities. To bridge these gaps, we release
POLYGUARD, a new state-of-the-art multilingual safety model for safeguarding
LLM generations, and the corresponding training and evaluation datasets.
POLYGUARD is trained on POLYGUARDMIX, the largest multilingual safety training
corpus to date containing 1.91M samples across 17 languages (e.g., Chinese,
Czech, English, Hindi). We also introduce POLYGUARDPROMPTS, a high quality
multilingual benchmark with 29K samples for the evaluation of safety
guardrails. Created by combining naturally occurring multilingual human-LLM
interactions and human-verified machine translations of an English-only safety
dataset (WildGuardMix; Han et al., 2024), our datasets contain prompt-output
pairs with labels of prompt harmfulness, response harmfulness, and response
refusal. Through extensive evaluations across multiple safety and toxicity
benchmarks, we demonstrate that POLYGUARD outperforms existing state-of-the-art
open-weight and commercial safety classifiers by 5.5%. Our contributions
advance efforts toward safer multilingual LLMs for all global users.
