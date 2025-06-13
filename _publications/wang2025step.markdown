---
layout: publication
title: 'Steca: Step-level Trajectory Calibration For LLM Agent Learning'
authors: Hanlin Wang, Jian Wang, Chak Tou Leong, Wenjie Li
conference: "Arxiv"
year: 2025
bibkey: wang2025step
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14276"}
  - {name: "Code", url: "https://github.com/WangHanLinHenry/STeCa"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Has Code']
---
Large language model (LLM)-based agents have shown promise in tackling complex tasks by interacting dynamically with the environment. Existing work primarily focuses on behavior cloning from expert demonstrations or preference learning through exploratory trajectory sampling. However, these methods often struggle to address long-horizon tasks, where suboptimal actions accumulate step by step, causing agents to deviate from correct task trajectories. To address this, we highlight the importance of timely calibration and the need to automatically construct calibration trajectories for training agents. We propose Step-Level Trajectory Calibration (STeCa), a novel framework for LLM agent learning. Specifically, STeCa identifies suboptimal actions through a step-level reward comparison during exploration. It constructs calibrated trajectories using LLM-driven reflection, enabling agents to learn from improved decision-making processes. We finally leverage these calibrated trajectories with successful trajectories for reinforced training. Extensive experiments demonstrate that STeCa significantly outperforms existing methods. Further analysis highlights that timely calibration enables agents to complete tasks with greater robustness. Our code and data are available at https://github.com/WangHanLinHenry/STeCa.
