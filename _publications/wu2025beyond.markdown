---
layout: publication
title: 'Beyond Templates: Dynamic Adaptation Of Reasoning Demonstrations Via Feasibility-aware Exploration'
authors: Yong Wu, Weihang Pan, Ke Li, Chen Binhui, Ping Li, Binbin Lin
conference: "Arxiv"
year: 2025
bibkey: wu2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20700"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) have shown remarkable reasoning capabilities, yet aligning such abilities to small language models (SLMs) remains a challenge due to distributional mismatches and limited model capacity. Existing reasoning datasets, typically designed for powerful LLMs, often lead to degraded performance when directly applied to weaker models. In this work, we introduce Dynamic Adaptation of Reasoning Trajectories (DART), a novel data adaptation framework that bridges the capability gap between expert reasoning trajectories and diverse SLMs. Instead of uniformly imitating expert steps, DART employs a selective imitation strategy guided by step-wise adaptability estimation via solution simulation. When expert steps surpass the student's capacity -- signaled by an Imitation Gap -- the student autonomously explores alternative reasoning paths, constrained by outcome consistency. We validate DART across multiple reasoning benchmarks and model scales, demonstrating that it significantly improves generalization and data efficiency over static fine-tuning. Our method enhances supervision quality by aligning training signals with the student's reasoning capabilities, offering a scalable solution for reasoning alignment in resource-constrained models.
