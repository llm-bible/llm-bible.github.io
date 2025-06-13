---
layout: publication
title: 'Evolutionary Optimization Of Model Merging Recipes'
authors: Takuya Akiba, Makoto Shing, Yujin Tang, Qi Sun, David Ha
conference: "Nat Mach Intell (2025)"
year: 2024
bibkey: akiba2024evolutionary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13187"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Merging']
---
Large language models (LLMs) have become increasingly capable, but their
development often requires substantial computational resources. While model
merging has emerged as a cost-effective promising approach for creating new
models by combining existing ones, it currently relies on human intuition and
domain knowledge, limiting its potential. Here, we propose an evolutionary
approach that overcomes this limitation by automatically discovering effective
combinations of diverse open-source models, harnessing their collective
intelligence without requiring extensive additional training data or compute.
Our approach operates in both parameter space and data flow space, allowing for
optimization beyond just the weights of the individual models. This approach
even facilitates cross-domain merging, generating models like a Japanese LLM
with Math reasoning capabilities. Surprisingly, our Japanese Math LLM achieved
state-of-the-art performance on a variety of established Japanese LLM
benchmarks, even surpassing models with significantly more parameters, despite
not being explicitly trained for such tasks. Furthermore, a culturally-aware
Japanese VLM generated through our approach demonstrates its effectiveness in
describing Japanese culture-specific content, outperforming previous Japanese
VLMs. This work not only contributes new state-of-the-art models back to the
open-source community, but also introduces a new paradigm for automated model
composition, paving the way for exploring alternative, efficient approaches to
foundation model development.
