---
layout: publication
title: 'Hephaestus: Improving Fundamental Agent Capabilities Of Large Language Models Through Continual Pre-training'
authors: Yuchen Zhuang, Jingfeng Yang, Haoming Jiang, Xin Liu, Kewei Cheng, Sanket Lokegaonkar, Yifan Gao, Qing Ping, Tianyi Liu, Binxuan Huang, Zheng Li, Zhengyang Wang, Pei Chen, Ruijie Wang, Rongzhi Zhang, Nasser Zalmout, Priyanka Nigam, Bing Yin, Chao Zhang
conference: "Arxiv"
year: 2025
bibkey: zhuang2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06589'}
tags: ['Large-Scale Training', 'Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Scaling Laws', 'Fine-Tuning', 'Prompting', 'Model Architecture', 'Pre-Training', 'Pretraining Methods']
---
Due to the scarcity of agent-oriented pre-training data, LLM-based autonomous
agents typically rely on complex prompting or extensive fine-tuning, which
often fails to introduce new capabilities while preserving strong
generalizability. We introduce Hephaestus-Forge, the first large-scale
pre-training corpus designed to enhance the fundamental capabilities of LLM
agents in API function calling, intrinsic reasoning and planning, and adapting
to environmental feedback. Hephaestus-Forge comprises 103B agent-specific data
encompassing 76,537 APIs, including both tool documentation to introduce
knowledge of API functions and function calling trajectories to strengthen
intrinsic reasoning. To explore effective training protocols, we investigate
scaling laws to identify the optimal recipe in data mixing ratios. By continual
pre-training on Hephaestus-Forge, Hephaestus outperforms small- to medium-scale
open-source LLMs and rivals commercial LLMs on three agent benchmarks,
demonstrating the effectiveness of our pre-training corpus in enhancing
fundamental agentic capabilities and generalization of LLMs to new tasks or
environments.
