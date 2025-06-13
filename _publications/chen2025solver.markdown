---
layout: publication
title: 'Solver-informed RL: Grounding Large Language Models For Authentic Optimization Modeling'
authors: Yitian Chen, Jingfan Xia, Siyu Shao, Dongdong Ge, Yinyu Ye
conference: "Arxiv"
year: 2025
bibkey: chen2025solver
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.11792'}
  - {name: "Code", url: 'https://github.com/Cardinal-Operations/SIRL'}
tags: ['Agentic', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Optimization modeling is fundamental to decision-making across diverse domains. Despite progress in automating optimization formulation from natural language descriptions, Large Language Models (LLMs) often struggle to generate formally correct and usable models against hallucinations, posing a challenge for reliable automation. Inspired by the success of Reinforcement Learning (RL) in enhancing Large Reasoning Models, we present Solver-Informed Reinforcement Learning (SIRL), a novel framework that significantly improves the authenticity of LLMs for optimization modeling using Reinforcement Learning with Verifiable Reward by leveraging external optimization solvers as verifiers. These verifiers automatically assess the executable code and the instance-level mathematical model represented by the associated LP file, yielding precise and comprehensive feedback signals -- including syntax, feasibility, and solution quality, serving as direct rewards for the RL process. This automated verification process, particularly from classic optimization solvers, also underpins our instance-enhanced self-consistency method to synthesize high-quality training data. Extensive experiments on diverse public benchmarks demonstrate that SIRL achieves state-of-the-art performance, substantially outperforming existing methods in generating accurate and executable optimization models. Our code is publicly available at https://github.com/Cardinal-Operations/SIRL.
