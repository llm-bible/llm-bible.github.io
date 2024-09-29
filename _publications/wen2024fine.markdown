---
layout: publication
title: On-Policy Fine-grained Knowledge Feedback for Hallucination Mitigation
authors: Wen Xueru, Lu Xinyu, Guan Xinyan, Lu Yaojie, Lin Hongyu, He Ben, Han Xianpei, Sun Le
conference: "Arxiv"
year: 2024
bibkey: wen2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12221"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Reinforcement Learning', 'Tools']
---
Hallucination occurs when large language models (LLMs) exhibit behavior that deviates from the boundaries of their knowledge during the response generation process. Previous learning-based methods focus on detecting knowledge boundaries and finetuning models with instance-level feedback but they suffer from inaccurate signals due to off-policy data sampling and coarse-grained feedback. In this paper we introduce einforcement earning or allucination (RLFH) a fine-grained feedback-based online reinforcement learning method for hallucination mitigation. Unlike previous learning-based methods RLFH enables LLMs to explore the boundaries of their internal knowledge and provide on-policy fine-grained feedback on these explorations. To construct fine-grained feedback for learning reliable generation behavior RLFH decomposes the outcomes of large models into atomic facts provides statement-level evaluation signals and traces back the signals to the tokens of the original responses. Finally RLFH adopts the online reinforcement algorithm with these token-level rewards to adjust model behavior for hallucination mitigation. For effective on-policy optimization RLFH also introduces an LLM-based fact assessment framework to verify the truthfulness and helpfulness of atomic facts without human intervention. Experiments on HotpotQA SQuADv2 and Biography benchmarks demonstrate that RLFH can balance their usage of internal knowledge during the generation process to eliminate the hallucination behavior of LLMs.
