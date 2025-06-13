---
layout: publication
title: 'Harnessing Large Language Models For Seed Generation In Greybox Fuzzing'
authors: Wenxuan Shi, Yunhang Zhang, Xinyu Xing, Jun Xu
conference: "Arxiv"
year: 2024
bibkey: shi2024harnessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.18143'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Fine-Tuning', 'Reinforcement Learning']
---
Greybox fuzzing has emerged as a preferred technique for discovering software
bugs, striking a balance between efficiency and depth of exploration. While
research has focused on improving fuzzing techniques, the importance of
high-quality initial seeds remains critical yet often overlooked. Existing
methods for seed generation are limited, especially for programs with
non-standard or custom input formats. Large Language Models (LLMs) has
revolutionized numerous domains, showcasing unprecedented capabilities in
understanding and generating complex patterns across various fields of
knowledge. This paper introduces SeedMind, a novel system that leverages LLMs
to boost greybox fuzzing through intelligent seed generation. Unlike previous
approaches, SeedMind employs LLMs to create test case generators rather than
directly producing test cases. Our approach implements an iterative,
feedback-driven process that guides the LLM to progressively refine test case
generation, aiming for increased code coverage depth and breadth. In developing
SeedMind, we addressed key challenges including input format limitations,
context window constraints, and ensuring consistent, progress-aware behavior.
Intensive evaluations with real-world applications show that SeedMind
effectively harnesses LLMs to generate high-quality test cases and facilitate
fuzzing in bug finding, presenting utility comparable to human-created seeds
and significantly outperforming the existing LLM-based solutions.
