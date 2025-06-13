---
layout: publication
title: 'KARMA: Augmenting Embodied AI Agents With Long-and-short Term Memory Systems'
authors: Zixuan Wang, Bo Yu, Junzhe Zhao, Wenhao Sun, Sai Hou, Shuai Liang, Xing Hu, Yinhe Han, Yiming Gan
conference: "Arxiv"
year: 2024
bibkey: wang2024augmenting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14908'}
  - {name: "Code", url: 'https://youtu.be/4BT7fnw9ehs'}
  - {name: "Code", url: 'https://github.com/WZX0Swarm0Robotics/KARMA/tree/master'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Embodied AI agents responsible for executing interconnected, long-sequence
household tasks often face difficulties with in-context memory, leading to
inefficiencies and errors in task execution. To address this issue, we
introduce KARMA, an innovative memory system that integrates long-term and
short-term memory modules, enhancing large language models (LLMs) for planning
in embodied agents through memory-augmented prompting. KARMA distinguishes
between long-term and short-term memory, with long-term memory capturing
comprehensive 3D scene graphs as representations of the environment, while
short-term memory dynamically records changes in objects' positions and states.
This dual-memory structure allows agents to retrieve relevant past scene
experiences, thereby improving the accuracy and efficiency of task planning.
Short-term memory employs strategies for effective and adaptive memory
replacement, ensuring the retention of critical information while discarding
less pertinent data. Compared to state-of-the-art embodied agents enhanced with
memory, our memory-augmented embodied AI agent improves success rates by 1.3x
and 2.3x in Composite Tasks and Complex Tasks within the AI2-THOR simulator,
respectively, and enhances task execution efficiency by 3.4x and 62.7x.
Furthermore, we demonstrate that KARMA's plug-and-play capability allows for
seamless deployment on real-world robotic systems, such as mobile manipulation
platforms.Through this plug-and-play memory system, KARMA significantly
enhances the ability of embodied agents to generate coherent and contextually
appropriate plans, making the execution of complex household tasks more
efficient. The experimental videos from the work can be found at
https://youtu.be/4BT7fnw9ehs. Our code is available at
https://github.com/WZX0Swarm0Robotics/KARMA/tree/master.
