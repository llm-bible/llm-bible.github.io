---
layout: publication
title: 'Imaginebench: Evaluating Reinforcement Learning With Large Language Model Rollouts'
authors: Jing-cheng Pang, Kaiyuan Li, Yidi Wang, Si-hang Yang, Shengyi Jiang, Yang Yu
conference: "Arxiv"
year: 2025
bibkey: pang2025evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10010'}
  - {name: "Code", url: 'https://github.com/LAMDA-RL/ImagineBench'}
tags: ['Agentic', 'Has Code', 'RAG', 'Training Techniques', 'Merging', 'Reinforcement Learning']
---
A central challenge in reinforcement learning (RL) is its dependence on extensive real-world interaction data to learn task-specific policies. While recent work demonstrates that large language models (LLMs) can mitigate this limitation by generating synthetic experience (noted as imaginary rollouts) for mastering novel tasks, progress in this emerging field is hindered due to the lack of a standard benchmark. To bridge this gap, we introduce ImagineBench, the first comprehensive benchmark for evaluating offline RL algorithms that leverage both real rollouts and LLM-imaginary rollouts. The key features of ImagineBench include: (1) datasets comprising environment-collected and LLM-imaginary rollouts; (2) diverse domains of environments covering locomotion, robotic manipulation, and navigation tasks; and (3) natural language task instructions with varying complexity levels to facilitate language-conditioned policy learning. Through systematic evaluation of state-of-the-art offline RL algorithms, we observe that simply applying existing offline RL algorithms leads to suboptimal performance on unseen tasks, achieving 35.44% success rate in hard tasks in contrast to 64.37% of method training on real rollouts for hard tasks. This result highlights the need for algorithm advancements to better leverage LLM-imaginary rollouts. Additionally, we identify key opportunities for future research: including better utilization of imaginary rollouts, fast online adaptation and continual learning, and extension to multi-modal tasks. Our code is publicly available at https://github.com/LAMDA-RL/ImagineBench.
