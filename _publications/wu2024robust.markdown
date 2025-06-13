---
layout: publication
title: 'Robust RL With Llm-driven Data Synthesis And Policy Adaptation For Autonomous Driving'
authors: Sihao Wu, Jiaxu Liu, Xiangyu Yin, Guangliang Cheng, Xingyu Zhao, Meng Fang, Xinping Yi, Xiaowei Huang
conference: "Arxiv"
year: 2024
bibkey: wu2024robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12568"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'Merging', 'Pretraining Methods', 'Fine-Tuning']
---
The integration of Large Language Models (LLMs) into autonomous driving
systems demonstrates strong common sense and reasoning abilities, effectively
addressing the pitfalls of purely data-driven methods. Current LLM-based agents
require lengthy inference times and face challenges in interacting with
real-time autonomous driving environments. A key open question is whether we
can effectively leverage the knowledge from LLMs to train an efficient and
robust Reinforcement Learning (RL) agent. This paper introduces RAPID, a novel
\underline\{\textbf\{R\}\}obust \underline\{\textbf\{A\}\}daptive
\underline\{\textbf\{P\}\}olicy \underline\{\textbf\{I\}\}nfusion and
\underline\{\textbf\{D\}\}istillation framework, which trains specialized
mix-of-policy RL agents using data synthesized by an LLM-based driving agent
and online adaptation. RAPID features three key designs: 1) utilization of
offline data collected from an LLM agent to distil expert knowledge into RL
policies for faster real-time inference; 2) introduction of robust distillation
in RL to inherit both performance and robustness from LLM-based teacher; and 3)
employment of a mix-of-policy approach for joint decision decoding with a
policy adapter. Through fine-tuning via online environment interaction, RAPID
reduces the forgetting of LLM knowledge while maintaining adaptability to
different tasks. Extensive experiments demonstrate RAPID's capability to
effectively integrate LLM knowledge into scaled-down RL policies in an
efficient, adaptable, and robust way. Code and checkpoints will be made
publicly available upon acceptance.
