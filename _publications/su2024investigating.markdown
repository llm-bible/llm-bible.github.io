---
layout: publication
title: 'Investigating Video Reasoning Capability Of Large Language Models With Tropes In Movies'
authors: Su Hung-ting, Chao Chun-tong, Hsu Ya-ching, Lin Xudong, Niu Yulei, Lee Hung-yi, Hsu Winston H.
conference: "Arxiv"
year: 2024
bibkey: su2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10923"}
  - {name: "Code", url: "https://ander1119.github.io/TiM"}
tags: ['Fine Tuning', 'Has Code', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated effectiveness not only in
language tasks but also in video reasoning. This paper introduces a novel
dataset, Tropes in Movies (TiM), designed as a testbed for exploring two
critical yet previously overlooked video reasoning skills: (1) Abstract
Perception: understanding and tokenizing abstract concepts in videos, and (2)
Long-range Compositional Reasoning: planning and integrating intermediate
reasoning steps for understanding long-range videos with numerous frames.
Utilizing tropes from movie storytelling, TiM evaluates the reasoning
capabilities of state-of-the-art LLM-based approaches. Our experiments show
that current methods, including Captioner-Reasoner, Large Multimodal Model
Instruction Fine-tuning, and Visual Programming, only marginally outperform a
random baseline when tackling the challenges of Abstract Perception and
Long-range Compositional Reasoning. To address these deficiencies, we propose
Face-Enhanced Viper of Role Interactions (FEVoRI) and Context Query Reduction
(ConQueR), which enhance Visual Programming by fostering role interaction
awareness and progressively refining movie contexts and trope queries during
reasoning processes, significantly improving performance by 15 F1 points.
However, this performance still lags behind human levels (40 vs. 65 F1).
Additionally, we introduce a new protocol to evaluate the necessity of Abstract
Perception and Long-range Compositional Reasoning for task resolution. This is
done by analyzing the code generated through Visual Programming using an
Abstract Syntax Tree (AST), thereby confirming the increased complexity of TiM.
The dataset and code are available at: https://ander1119.github.io/TiM
