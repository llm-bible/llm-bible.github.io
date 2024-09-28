---
layout: publication
title: Reinforcement Learning from Reflective Feedback (RLRF) Aligning and Improving LLMs via Fine-Grained Self-Reflection
authors: Lee Kyungjae, Hwang Dasol, Park Sunghyun, Jang Youngsoo, Lee Moontae
conference: "Arxiv"
year: 2024
bibkey: lee2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14238"}
tags: ['Pretraining Methods', 'LLM', 'Arxiv']
---
Despite the promise of RLHF in aligning LLMs with human preferences it often leads to superficial alignment prioritizing stylistic changes over improving downstream performance of LLMs. Underspecified preferences could obscure directions to align the models. Lacking exploration restricts identification of desirable outputs to improve the models. To overcome these challenges we propose a novel framework Reinforcement Learning from Reflective Feedback (RLRF) which leverages fine-grained feedback based on detailed criteria to improve the core capabilities of LLMs. RLRF employs a self-reflection mechanism to systematically explore and refine LLM responses then fine-tuning the models via a RL algorithm along with promising responses. Our experiments across Just-Eval Factuality and Mathematical Reasoning demonstrate the efficacy and transformative potential of RLRF beyond superficial surface-level adjustment.
