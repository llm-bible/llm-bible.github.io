---
layout: publication
title: 'Tailoring Self-rationalizers With Multi-reward Distillation'
authors: Sahana Ramnath, Brihi Joshi, Skyler Hallinan, Ximing Lu, Liunian Harold Li, Aaron Chan, Jack Hessel, Yejin Choi, Xiang Ren
conference: "The Twelfth International Conference on Learning Representations 2024"
year: 2023
bibkey: ramnath2023tailoring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02805"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Large language models (LMs) are capable of generating free-text rationales to
aid question answering. However, prior work 1) suggests that useful
self-rationalization is emergent only at significant scales (e.g., 175B
parameter GPT-3); and 2) focuses largely on downstream performance, ignoring
the semantics of the rationales themselves, e.g., are they faithful, true, and
helpful for humans? In this work, we enable small-scale LMs (approx. 200x
smaller than GPT-3) to generate rationales that not only improve downstream
task performance, but are also more plausible, consistent, and diverse,
assessed both by automatic and human evaluation. Our method, MaRio
(Multi-rewArd RatIOnalization), is a multi-reward conditioned
self-rationalization algorithm that optimizes multiple distinct properties like
plausibility, diversity and consistency. Results on five difficult
question-answering datasets StrategyQA, QuaRel, OpenBookQA, NumerSense and QASC
show that not only does MaRio improve task accuracy, but it also improves the
self-rationalization quality of small LMs across the aforementioned axes better
than a supervised fine-tuning (SFT) baseline. Extensive human evaluations
confirm that MaRio rationales are preferred vs. SFT rationales, as well as
qualitative improvements in plausibility and consistency.
