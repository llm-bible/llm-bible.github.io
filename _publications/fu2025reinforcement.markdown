---
layout: publication
title: 'RLAE: Reinforcement Learning-assisted Ensemble For Llms'
authors: Yuqian Fu, Yuanheng Zhu, Jiajun Chai, Guojun Yin, Wei Lin, Qichao Zhang, Dongbin Zhao
conference: "Arxiv"
year: 2025
bibkey: fu2025reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00439"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Ensembling large language models (LLMs) can effectively combine diverse strengths of different models, offering a promising approach to enhance performance across various tasks. However, existing methods typically rely on fixed weighting strategies that fail to adapt to the dynamic, context-dependent characteristics of LLM capabilities. In this work, we propose Reinforcement Learning-Assisted Ensemble for LLMs (RLAE), a novel framework that reformulates LLM ensemble through the lens of a Markov Decision Process (MDP). Our approach introduces a RL agent that dynamically adjusts ensemble weights by considering both input context and intermediate generation states, with the agent being trained using rewards that directly correspond to the quality of final outputs. We implement RLAE using both single-agent and multi-agent reinforcement learning algorithms (\\(\text\{RLAE\}_\text\{PPO\}\\) and \\(\text\{RLAE\}_\text\{MAPPO\}\\) ), demonstrating substantial improvements over conventional ensemble methods. Extensive evaluations on a diverse set of tasks show that RLAE outperforms existing approaches by up to \\(3.3%\\) accuracy points, offering a more effective framework for LLM ensembling. Furthermore, our method exhibits superior generalization capabilities across different tasks without the need for retraining, while simultaneously achieving lower time latency.
