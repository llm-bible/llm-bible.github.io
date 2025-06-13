---
layout: publication
title: 'REINFORCE++: An Efficient RLHF Algorithm With Robustness To Both Prompt And Reward Models'
authors: Jian Hu, Jason Klein Liu, Wei Shen
conference: "Arxiv"
year: 2025
bibkey: hu2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03262"}
  - {name: "Code", url: "https://github.com/OpenRLHF/OpenRLHF"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Efficiency and Optimization', 'Reinforcement Learning', 'GPT', 'Has Code', 'Prompting', 'Applications']
---
Reinforcement Learning from Human Feedback (RLHF) plays a crucial role in
aligning large language models (LLMs) with human values and preferences. While
state-of-the-art applications like ChatGPT/GPT-4 commonly employ Proximal
Policy Optimization (PPO), the inclusion of a critic network introduces
significant computational overhead. REINFORCE-based methods, such as REINFORCE
Leave One-Out (RLOO), ReMax, and Group Relative Policy Optimization (GRPO),
address this limitation by eliminating the critic network. However, these
approaches face challenges in accurate advantage estimation. Specifically, they
estimate advantages independently for responses to each prompt, which can lead
to overfitting on simpler prompts and vulnerability to reward hacking. To
address these challenges, we introduce REINFORCE++, a novel approach that
removes the critic model while using the normalized reward of a batch as the
baseline. Our empirical evaluation demonstrates that REINFORCE++ exhibits
robust performance across various reward models without requiring prompt set
truncation. Furthermore, it achieves superior generalization in both RLHF and
long chain-of-thought (CoT) settings compared to existing REINFORCE-based
methods. The implementation is available at
https://github.com/OpenRLHF/OpenRLHF.
