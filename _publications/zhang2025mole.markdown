---
layout: publication
title: 'Mole-vla: Dynamic Layer-skipping Vision Language Action Model Via Mixture-of-layers For Efficient Robot Manipulation'
authors: Rongyu Zhang, Menghang Dong, Yuan Zhang, Liang Heng, Xiaowei Chi, Gaole Dai, Li Du, Yuan Du, Shanghang Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025mole
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.20384'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Tools', 'Pruning', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal Large Language Models (MLLMs) excel in understanding complex
language and visual data, enabling generalist robotic systems to interpret
instructions and perform embodied tasks. Nevertheless, their real-world
deployment is hindered by substantial computational and storage demands. Recent
insights into the homogeneous patterns in the LLM layer have inspired
sparsification techniques to address these challenges, such as early exit and
token pruning. However, these methods often neglect the critical role of the
final layers that encode the semantic information most relevant to downstream
robotic tasks. Aligning with the recent breakthrough of the Shallow Brain
Hypothesis (SBH) in neuroscience and the mixture of experts in model
sparsification, we conceptualize each LLM layer as an expert and propose a
Mixture-of-Layers Vision-Language-Action model (MoLe-VLA, or simply MoLe)
architecture for dynamic LLM layer activation. We introduce a Spatial-Temporal
Aware Router (STAR) for MoLe to selectively activate only parts of the layers
based on the robot's current state, mimicking the brain's distinct signal
pathways specialized for cognition and causal reasoning. Additionally, to
compensate for the cognitive ability of LLMs lost in MoLe, we devise a
Cognition Self-Knowledge Distillation (CogKD) framework. CogKD enhances the
understanding of task demands and improves the generation of task-relevant
action sequences by leveraging cognitive features. Extensive experiments
conducted in both RLBench simulation and real-world environments demonstrate
the superiority of MoLe-VLA in both efficiency and performance. Specifically,
MoLe-VLA achieves an 8% improvement in the mean success rate across ten tasks
while reducing computational costs by up to x5.6 compared to standard LLMs.
