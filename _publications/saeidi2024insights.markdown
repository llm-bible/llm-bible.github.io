---
layout: publication
title: 'Insights Into Alignment: Evaluating DPO And Its Variants Across Multiple Tasks'
authors: Amir Saeidi, Shivanshu Verma, Md Nayem Uddin, Chitta Baral
conference: "Arxiv"
year: 2024
bibkey: saeidi2024insights
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14723"}
tags: ['Fine-Tuning', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning']
---
This study evaluates Direct Preference Optimization (DPO) and its variants
for aligning Large Language Models (LLMs) with human preferences, testing three
configurations: (1) with Supervised Fine Tuning (SFT), (2) without SFT, and (3)
without SFT but using an instruction tuned model. We further investigate how
training set size influences model performance. Our evaluation spans 13
benchmarks covering dialogue, reasoning, mathematical problem-solving, question
answering, truthfulness, MT-Bench, Big Bench, and the Open LLM Leaderboard. We
find that: (1) alignment methods often achieve near optimal performance even
with smaller subsets of training data; (2) although they offer limited
improvements on complex reasoning tasks, they enhance mathematical
problem-solving; and (3) using an instruction tuned model improves
truthfulness. These insights highlight the conditions under which alignment
methods excel, as well as their limitations.
