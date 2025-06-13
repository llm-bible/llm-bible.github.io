---
layout: publication
title: '\(d^2lora\): Data-driven Lora Initialization For Low Resource Tasks'
authors: Javad Seraj, Mohammad Mahdi Mohajeri, Mohammad Javad Dousti
conference: "Arxiv"
year: 2025
bibkey: seraj2025data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18089"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Tuning large language models is essential for optimizing their performance
across diverse applications, particularly in scenarios with limited data
availability. Tuning large language models in scarce data scenarios is crucial,
particularly given that the convergence speed of the LoRA method is lower than
that of full fine-tuning. In this paper, we present an analysis of
post-training methods including Supervised Fine-Tuning (SFT), Direct Preference
Optimization (DPO), and Odds Ratio Preference Optimization (ORPO) within the
context of task-specific learning using the LoRA method. Next we introduce
\\(D^2LoRA\\), a data-driven approach for initializing LoRA metrics that enhances
training efficiency, especially in limited-data settings. Our experiments
compare \\(D^2LoRA\\) with vanilla LoRA in terms of performance and catastrophic
forgetting under extremely data-constrained conditions. The results demonstrate
that \\(D^2LoRA\\) achieves a 1% improvement GSM8K benchmark and a 2-point
improvement in ROUGE score in title generation tasks. \\(D^2LoRA\\) facilitates the
adaptation of LLMs to multiple tasks even when task-specific data is scarce,
thereby reducing training expenses and offering data cost.
