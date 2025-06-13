---
layout: publication
title: 'Teaching AI To Handle Exceptions: Supervised Fine-tuning With Human-aligned Judgment'
authors: Matthew Dossantos Disorbo, Harang Ju, Sinan Aral
conference: "Arxiv"
year: 2025
bibkey: disorbo2025teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02976"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Interpretability and Explainability', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs), initially developed for generative AI, are now
evolving into agentic AI systems, which make decisions in complex, real-world
contexts. Unfortunately, while their generative capabilities are
well-documented, their decision-making processes remain poorly understood. This
is particularly evident when models are handling exceptions, a critical and
challenging aspect of decision-making made relevant by the inherent
incompleteness of contracts. Here we demonstrate that LLMs, even ones that
excel at reasoning, deviate significantly from human judgments because they
adhere strictly to policies, even when such adherence is impractical,
suboptimal, or even counterproductive. We then evaluate three approaches to
tuning AI agents to handle exceptions: ethical framework prompting,
chain-of-thought reasoning, and supervised fine-tuning. We find that while
ethical framework prompting fails and chain-of-thought prompting provides only
slight improvements, supervised fine-tuning, specifically with human
explanations, yields markedly better results. Surprisingly, in our experiments,
supervised fine-tuning even enabled models to generalize human-like
decision-making to novel scenarios, demonstrating transfer learning of
human-aligned decision-making across contexts. Furthermore, fine-tuning with
explanations, not just labels, was critical for alignment, suggesting that
aligning LLMs with human judgment requires explicit training on how decisions
are made, not just which decisions are made. These findings highlight the need
to address LLMs' shortcomings in handling exceptions in order to guide the
development of agentic AI toward models that can effectively align with human
judgment and simultaneously adapt to novel contexts.
