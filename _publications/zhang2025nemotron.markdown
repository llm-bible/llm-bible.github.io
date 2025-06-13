---
layout: publication
title: 'Nemotron-research-tool-n1: Exploring Tool-using Language Models With Reinforced Reasoning'
authors: Shaokun Zhang, Yi Dong, Jieyu Zhang, Jan Kautz, Bryan Catanzaro, Andrew Tao, Qingyun Wu, Zhiding Yu, Guilin Liu
conference: "Arxiv"
year: 2025
bibkey: zhang2025nemotron
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00024"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Enabling large language models with external tools has become a pivotal strategy for extending their functionality beyond text space. To enhance LLMs' tool-calling abilities, previous approaches primarily rely on supervised fine-tuning (SFT) with trajectories distilled from stronger models, often resulting in imitative reasoning that limits generalization. In this work, we explore rule-based reinforcement learning to enhance tool-calling in LLMs, resulting in Nemotron-Research-Tool-N1, a series of tool-calling reasoning models. Rather than enforcing supervision over intermediate distilled reasoning traces, Tool-N1 is trained with a binary RL reward that assesses only the format validity and functional correctness of tool invocations. This lightweight supervision allows the model to develop reasoning strategies independently, without relying on annotated trajectories. Experiments on several major benchmarks show that Tool-N1-7B/14B clearly outperform GPT-4o. We conduct a systematic study on the design of rule-based reinforcement learning strategies for training tool-calling models. Using 5,518 distilled reasoning trajectories, we compare SFT, RL, and the SFT-then-RL pipeline, finding that the widely adopted SFT-then-RL paradigm does not necessarily outperform pure RL.
