---
layout: publication
title: 'Unified Preference Optimization: Language Model Alignment Beyond The Preference Frontier'
authors: Anirudhan Badrinath, Prabhat Agarwal, Jiajing Xu
conference: "Arxiv"
year: 2024
bibkey: badrinath2024unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17956"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
For aligning large language models (LLMs), prior work has leveraged reinforcement learning via human feedback (RLHF) or variations of direct preference optimization (DPO). While DPO offers a simpler framework based on maximum likelihood estimation, it compromises on the ability to easily tune language models to maximize auxiliary, non-preferential objectives according to the LLM designer's preferences (e.g., tuning lexical style or minimizing specific kinds of harmful content). Critically, these designer objectives may not be amply human-labeled or represented in available data, align with user preferences, or even be able to be captured tractably by binary preference pairs. To leverage the simplicity and performance of DPO with the generality of RL, we propose a unified approach. Based on a simple decomposition of preference and auxiliary objectives, we allow for tuning LLMs to optimize user and designer preferences without any additional specialized or preference data, computational cost, stability ``tweaks'', or training instability. The proposed method, Unified Preference Optimization, shows the ability to effectively generalize to user preferences and auxiliary objectives, while preserving or surpassing alignment performance on challenging benchmarks across a range of model sizes.
