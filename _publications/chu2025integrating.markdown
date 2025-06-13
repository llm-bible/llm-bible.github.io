---
layout: publication
title: 'Graspcot: Integrating Physical Property Reasoning For 6-dof Grasping Under Flexible Language Instructions'
authors: Xiaomeng Chu, Jiajun Deng, Guoliang You, Wei Liu, Xingchen Li, Jianmin Ji, Yanyong Zhang
conference: "Arxiv"
year: 2025
bibkey: chu2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16013"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Applications']
---
Flexible instruction-guided 6-DoF grasping is a significant yet challenging
task for real-world robotic systems. Existing methods utilize the contextual
understanding capabilities of the large language models (LLMs) to establish
mappings between expressions and targets, allowing robots to comprehend users'
intentions in the instructions. However, the LLM's knowledge about objects'
physical properties remains underexplored despite its tight relevance to
grasping. In this work, we propose GraspCoT, a 6-DoF grasp detection framework
that integrates a Chain-of-Thought (CoT) reasoning mechanism oriented to
physical properties, guided by auxiliary question-answering (QA) tasks.
Particularly, we design a set of QA templates to enable hierarchical reasoning
that includes three stages: target parsing, physical property analysis, and
grasp action selection. Moreover, GraspCoT presents a unified multimodal LLM
architecture, which encodes multi-view observations of 3D scenes into 3D-aware
visual tokens, and then jointly embeds these visual tokens with CoT-derived
textual tokens within LLMs to generate grasp pose predictions. Furthermore, we
present IntentGrasp, a large-scale benchmark that fills the gap in public
datasets for multi-object grasp detection under diverse and indirect verbal
commands. Extensive experiments on IntentGrasp demonstrate the superiority of
our method, with additional validation in real-world robotic applications
confirming its practicality. Codes and data will be released.
