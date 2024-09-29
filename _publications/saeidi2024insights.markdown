---
layout: publication
title: Insights into Alignment Evaluating DPO and its Variants Across Multiple Tasks
authors: Saeidi Amir, Verma Shivanshu, Baral Chitta
conference: "Arxiv"
year: 2024
bibkey: saeidi2024insights
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14723"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable performance across a spectrum of tasks. Recently Direct Preference Optimization (DPO) has emerged as an RL-free approach to optimize the policy model on human preferences. However several limitations hinder the widespread adoption of this method. To address these shortcomings various versions of DPO have been introduced. Yet a comprehensive evaluation of these variants across diverse tasks is still lacking. In this study we aim to bridge this gap by investigating the performance of alignment methods across three distinct scenarios (1) keeping the Supervised Fine-Tuning (SFT) part (2) skipping the SFT part and (3) skipping the SFT part and utilizing an instruction-tuned model. Furthermore we explore the impact of different training sizes on their performance. Our evaluation spans a range of tasks including dialogue systems reasoning mathematical problem-solving question answering truthfulness and multi-task understanding encompassing 13 benchmarks such as MT-Bench Big Bench and Open LLM Leaderboard. Key observations reveal that alignment methods achieve optimal performance with smaller training data subsets exhibit limited effectiveness in reasoning tasks yet significantly impact mathematical problem-solving and employing an instruction-tuned model notably influences truthfulness. We anticipate that our findings will catalyze further research aimed at developing more robust models to address alignment challenges.
