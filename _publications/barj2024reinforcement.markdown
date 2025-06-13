---
layout: publication
title: 'Reinforcement Learning From LLM Feedback To Counteract Goal Misgeneralization'
authors: Houda Nait El Barj, Theophile Sautory
conference: "Arxiv"
year: 2024
bibkey: barj2024reinforcement
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.07181'}
tags: ['Agentic', 'RAG', 'Security', 'Training Techniques', 'Reinforcement Learning', 'Ethics and Bias']
---
We introduce a method to address goal misgeneralization in reinforcement
learning (RL), leveraging Large Language Model (LLM) feedback during training.
Goal misgeneralization, a type of robustness failure in RL occurs when an agent
retains its capabilities out-of-distribution yet pursues a proxy rather than
the intended one. Our approach utilizes LLMs to analyze an RL agent's policies
during training and identify potential failure scenarios. The RL agent is then
deployed in these scenarios, and a reward model is learnt through the LLM
preferences and feedback. This LLM-informed reward model is used to further
train the RL agent on the original dataset. We apply our method to a maze
navigation task, and show marked improvements in goal generalization,
especially in cases where true and proxy goals are somewhat distinguishable and
behavioral biases are pronounced. This study demonstrates how the LLM, despite
its lack of task proficiency, can efficiently supervise RL agents, providing
scalable oversight and valuable insights for enhancing goal-directed learning
in RL through the use of LLMs.
