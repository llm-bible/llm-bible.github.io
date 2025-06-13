---
layout: publication
title: 'Optimizing Safe And Aligned Language Generation: A Multi-objective GRPO Approach'
authors: Xuying Li, Zhuo Li, Yuji Kosuga, Victor Bian
conference: "Arxiv"
year: 2025
bibkey: li2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21819"}
tags: ['Responsible AI', 'Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning']
---
Aligning large language models (LLMs) with human values and safety
constraints is challenging, especially when objectives like helpfulness,
truthfulness, and avoidance of harm conflict. Reinforcement Learning from Human
Feedback (RLHF) has achieved notable success in steering models, but is complex
and can be unstable. Recent approaches such as Direct Preference Optimization
(DPO) simplify preference-based fine-tuning but may introduce bias or trade-off
certain objectives~\cite\{dpo\}. In this work, we propose a Group Relative Policy
Optimization (GRPO) framework with a multi-label reward regression model to
achieve safe and aligned language generation. The GRPO algorithm optimizes a
policy by comparing groups of sampled responses, eliminating the need for a
separate value critic and improving training efficiency~\cite\{grpo\}. We train a
reward model to predict multiple alignment scores (e.g., safety, helpfulness,
etc.), which are combined into a single reward signal. We provide a theoretical
derivation for using this learned multi-aspect reward within GRPO and discuss
its advantages and limitations. Empirically, our approach improves all the
safety and quality metrics evaluated in language generation tasks on model
scales (0.5B, 7B, and 14B parameters), demonstrating a robust balance of
objectives. We compare GRPO to PPO-based RLHF and DPO, highlighting that GRPO
achieves alignment with significantly lower computational cost and explicit
multi-objective handling. \textbf\{We will open-source all trained models at
https://huggingface.co/hydroxai.
