---
layout: publication
title: 'Climbing The Ladder Of Reasoning: What Llms Can-and Still Can''t-solve After SFT?'
authors: Yiyou Sun, Georgia Zhou, Hao Wang, Dacheng Li, Nouha Dziri, Dawn Song
conference: "Arxiv"
year: 2025
bibkey: sun2025climbing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11741"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods', 'Reinforcement Learning']
---
Recent supervised fine-tuning (SFT) approaches have significantly improved
language models' performance on mathematical reasoning tasks, even when models
are trained at a small scale. However, the specific capabilities enhanced
through such fine-tuning remain poorly understood. In this paper, we conduct a
detailed analysis of model performance on the AIME24 dataset to understand how
reasoning capabilities evolve. We discover a ladder-like structure in problem
difficulty, categorize questions into four tiers (Easy, Medium, Hard, and
Extremely Hard (Exh)), and identify the specific requirements for advancing
between tiers. We find that progression from Easy to Medium tier requires
adopting an R1 reasoning style with minimal SFT (500-1K instances), while
Hard-level questions suffer from frequent model's errors at each step of the
reasoning chain, with accuracy plateauing at around 65% despite logarithmic
scaling. Exh-level questions present a fundamentally different challenge; they
require unconventional problem-solving skills that current models uniformly
struggle with. Additional findings reveal that carefully curated small-scale
datasets offer limited advantage-scaling dataset size proves far more
effective. Our analysis provides a clearer roadmap for advancing language model
capabilities in mathematical reasoning.
