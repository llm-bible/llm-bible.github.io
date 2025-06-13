---
layout: publication
title: 'Response-level Rewards Are All You Need For Online Reinforcement Learning In Llms: A Mathematical Perspective'
authors: Shenghua He, Tian Xia, Xuan Zhou, Hui Wei
conference: "Arxiv"
year: 2025
bibkey: he2025response
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02553"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Applications', 'Ethics and Bias', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
We study a common challenge in reinforcement learning for large language models (LLMs): the Zero-Reward Assumption, where non-terminal actions (i.e., intermediate token generations) receive zero task-specific immediate reward, while only the final token receives a reward for the entire response. This assumption arises frequently in practice, as precise token-level rewards are often difficult or infeasible to obtain in LLM applications. In this work, we provide a unifying theoretical perspective. We introduce the Trajectory Policy Gradient Theorem, which shows that the policy gradient based on true, unknown token-level rewards can be unbiasedly estimated using only a response-level reward model, regardless of whether the Zero-Reward Assumption holds or not, for algorithms in the REINFORCE and Actor-Critic families. This result reveals that widely used methods such as PPO, GRPO, ReMax, and RLOO inherently possess the capacity to model token-level reward signals, offering a theoretical justification for response-level reward approaches. Our findings pave the way for more practical, efficient LLM fine-tuning, allowing developers to treat training algorithms as black boxes and focus on improving the response-level reward model with auxiliary sub-models. We also offer a detailed analysis of popular RL and non-RL methods, comparing their theoretical foundations and practical advantages across common LLM tasks. Finally, we propose a new algorithm: Token-Reinforced Policy Optimization (TRePO), a theoretically grounded method that is simpler than PPO, matches GRPO in memory efficiency, and holds promise for broad applicability.
