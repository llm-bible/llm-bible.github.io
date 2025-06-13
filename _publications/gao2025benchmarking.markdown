---
layout: publication
title: 'Benchmarking Multimodal Cot Reward Model Stepwise By Visual Program'
authors: Minghe Gao, Xuqi Liu, Zhongqi Yue, Yang Wu, Shuang Chen, Juncheng Li, Siliang Tang, Fei Wu, Tat-seng Chua, Yueting Zhuang
conference: "Arxiv"
year: 2025
bibkey: gao2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.06606'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Recent advancements in reward signal usage for Large Language Models (LLMs)
are remarkable. However, significant challenges exist when transitioning reward
signal to the multimodal domain, including labor-intensive annotations,
over-reliance on one-step rewards, and inadequate evaluation. To address these
issues, we propose SVIP, a novel approach to train a step-level
multi-dimensional Chain-of-Thought~(CoT) reward model automatically. It
generates code for solving visual tasks and transforms the analysis of code
blocks into the evaluation of CoT step as training samples. Then, we train
SVIP-Reward model using a multi-head attention mechanism called TriAtt-CoT. The
advantages of SVIP-Reward are evident throughout the entire process of MLLM. We
also introduce a benchmark for CoT reward model training and testing.
Experimental results demonstrate that SVIP-Reward improves MLLM performance
across training and inference-time scaling, yielding better results on
benchmarks while reducing hallucinations and enhancing reasoning ability.
