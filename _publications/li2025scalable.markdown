---
layout: publication
title: 'SOLAR: Scalable Optimization Of Large-scale Architecture For Reasoning'
authors: Chen Li, Yinyi Luo, Anudeep Bolimera, Uzair Ahmed, Shri Kiran Srinivasan, Hrishikesh Gokhale, Marios Savvides
conference: "Arxiv"
year: 2025
bibkey: li2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04530"}
tags: ['Tools', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Large Language Models excel in reasoning yet often rely on Chain-of-Thought prompts, limiting performance on tasks demanding more nuanced topological structures. We present SOLAR (Scalable Optimization of Large-scale Architecture for Reasoning), a framework that dynamically optimizes Chain-of-Thought (CoT), Tree-of-Thought (ToT), and Graph-of-Thought (GoT) topologies to boost accuracy and efficiency. Our Topological-Annotation-Generation (TAG) system automates dataset creation, annotation, and difficulty segmentation, leading to stronger post training and test-time performance. We also propose Topological-Scaling, a curriculum-learning-based approach that adaptively combines post training and inference scaling to each task. On MATH and GSM8K, SOLAR delivers notable gains: +5% accuracy with Topological Tuning, +9% with Topological Rewarding, and +10.02% with Hybrid Scaling, while reducing response length by over 5%, lowering inference latency. To further enhance efficiency, we introduce a multi-task Topological Reward Model (M-TRM) that selects both the optimal reasoning topology and final answer in a single pass, eliminating multiple single-task TRMs. Remarkably, M-TRM also surpasses all single-task TRMs, improving accuracy by +10% and rank correlation by +9%. Overall, SOLAR establishes a new benchmark for scalable, high-precision LLM reasoning and introduces a fully automated, dynamic topology competition mechanism.
