---
layout: publication
title: 'ELEMENTAL: Interactive Learning From Demonstrations And Vision-language Models For Reward Design In Robotics'
authors: Letian Chen, Nina Moorman, Matthew Gombolay
conference: "Arxiv"
year: 2024
bibkey: chen2024interactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18825"}
tags: ['Agentic', 'Security', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG']
---
Reinforcement learning (RL) has demonstrated compelling performance in robotic tasks, but its success often hinges on the design of complex, ad hoc reward functions. Researchers have explored how Large Language Models (LLMs) could enable non-expert users to specify reward functions more easily. However, LLMs struggle to balance the importance of different features, generalize poorly to out-of-distribution robotic tasks, and cannot represent the problem properly with only text-based descriptions. To address these challenges, we propose ELEMENTAL (intEractive LEarning froM dEmoNstraTion And Language), a novel framework that combines natural language guidance with visual user demonstrations to align robot behavior with user intentions better. By incorporating visual inputs, ELEMENTAL overcomes the limitations of text-only task specifications, while leveraging inverse reinforcement learning (IRL) to balance feature weights and match the demonstrated behaviors optimally. ELEMENTAL also introduces an iterative feedback-loop through self-reflection to improve feature, reward, and policy learning. Our experiment results demonstrate that ELEMENTAL outperforms prior work by 42.3% on task success, and achieves 41.3% better generalization in out-of-distribution tasks, highlighting its robustness in LfD.
