---
layout: publication
title: 'A Large Language Model-driven Reward Design Framework Via Dynamic Feedback For Reinforcement Learning'
authors: Shengjie Sun, Runze Liu, Jiafei Lyu, Jing-wen Yang, Liangpeng Zhang, Xiu Li
conference: "Arxiv"
year: 2024
bibkey: sun2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14660"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'ACL', 'Training Techniques']
---
Large Language Models (LLMs) have shown significant potential in designing
reward functions for Reinforcement Learning (RL) tasks. However, obtaining
high-quality reward code often involves human intervention, numerous LLM
queries, or repetitive RL training. To address these issues, we propose CARD, a
LLM-driven Reward Design framework that iteratively generates and improves
reward function code. Specifically, CARD includes a Coder that generates and
verifies the code, while a Evaluator provides dynamic feedback to guide the
Coder in improving the code, eliminating the need for human feedback. In
addition to process feedback and trajectory feedback, we introduce Trajectory
Preference Evaluation (TPE), which evaluates the current reward function based
on trajectory preferences. If the code fails the TPE, the Evaluator provides
preference feedback, avoiding RL training at every iteration and making the
reward function better aligned with the task objective. Empirical results on
Meta-World and ManiSkill2 demonstrate that our method achieves an effective
balance between task performance and token efficiency, outperforming or
matching the baselines across all tasks. On 10 out of 12 tasks, CARD shows
better or comparable performance to policies trained with expert-designed
rewards, and our method even surpasses the oracle on 3 tasks.
