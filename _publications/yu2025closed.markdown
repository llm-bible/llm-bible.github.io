---
layout: publication
title: 'SIPDO: Closed-loop Prompt Optimization Via Synthetic Data Feedback'
authors: Yaoning Yu, Ye Yu, Kai Wei, Haojing Luo, Haohan Wang
conference: "Arxiv"
year: 2025
bibkey: yu2025closed
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19514'}
tags: ['Efficiency and Optimization', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Prompt quality plays a critical role in the performance of large language models (LLMs), motivating a growing body of work on prompt optimization. Most existing methods optimize prompts over a fixed dataset, assuming static input distributions and offering limited support for iterative improvement. We introduce SIPDO (Self-Improving Prompts through Data-Augmented Optimization), a closed-loop framework for prompt learning that integrates synthetic data generation into the optimization process. SIPDO couples a synthetic data generator with a prompt optimizer, where the generator produces new examples that reveal current prompt weaknesses and the optimizer incrementally refines the prompt in response. This feedback-driven loop enables systematic improvement of prompt performance without assuming access to external supervision or new tasks. Experiments across question answering and reasoning benchmarks show that SIPDO outperforms standard prompt tuning methods, highlighting the value of integrating data synthesis into prompt learning workflows.
