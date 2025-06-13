---
layout: publication
title: 'Reasonflux: Hierarchical LLM Reasoning Via Scaling Thought Templates'
authors: Ling Yang, Zhaochen Yu, Bin Cui, Mengdi Wang
conference: "Arxiv"
year: 2025
bibkey: yang2025hierarchical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06772'}
  - {name: "Code", url: 'https://github.com/Gen-Verse/ReasonFlux'}
tags: ['RAG', 'Has Code', 'Tools']
---
We present that hierarchical LLM reasoning via scaling thought templates can
effectively optimize the reasoning search space and outperform the mathematical
reasoning capabilities of powerful LLMs like OpenAI o1-preview and DeepSeek V3.
We train our ReasonFlux-32B model with only 8 GPUs and introduces three
innovations: (i) a structured and generic thought template library, containing
around 500 high-level thought templates capable of generalizing to similar or
relevant reasoning problems; (ii) performing hierarchical reinforcement
learning on a sequence of thought templates instead of long CoTs, optimizing a
base LLM to plan out an optimal template trajectory for gradually handling
complex problems; (iii) a brand new inference scaling system that enables
hierarchical LLM reasoning by adaptively scaling thought templates at inference
time. With a template trajectory containing more explainable reasoning
structures than DeepSeek-R1 and o3-mini, our ReasonFlux-32B significantly
advances math reasoning capabilities to state-of-the-art levels. Notably, on
the MATH benchmark, it achieves an accuracy of 91.2% and surpasses o1-preview
by 6.7%. On the USA Math Olympiad (AIME) benchmark, ReasonFlux-32B solves an
average of 56.7% of problems, surpassing o1-preview and DeepSeek-V3 by 27% and
45%, respectively. Code: https://github.com/Gen-Verse/ReasonFlux
