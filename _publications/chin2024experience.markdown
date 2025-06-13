---
layout: publication
title: 'In-context Experience Replay Facilitates Safety Red-teaming Of Text-to-image Diffusion Models'
authors: Zhi-yi Chin, Mario Fritz, Pin-yu Chen, Wei-chen Chiu
conference: "Arxiv"
year: 2024
bibkey: chin2024experience
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16769"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Prompting']
---
Text-to-image (T2I) models have shown remarkable progress, but their
potential to generate harmful content remains a critical concern in the ML
community. While various safety mechanisms have been developed, the field lacks
systematic tools for evaluating their effectiveness against real-world misuse
scenarios. In this work, we propose ICER, a novel red-teaming framework that
leverages Large Language Models (LLMs) and a bandit optimization-based
algorithm to generate interpretable and semantic meaningful problematic prompts
by learning from past successful red-teaming attempts. Our ICER efficiently
probes safety mechanisms across different T2I models without requiring internal
access or additional training, making it broadly applicable to deployed
systems. Through extensive experiments, we demonstrate that ICER significantly
outperforms existing prompt attack methods in identifying model vulnerabilities
while maintaining high semantic similarity with intended content. By uncovering
that successful jailbreaking instances can systematically facilitate the
discovery of new vulnerabilities, our work provides crucial insights for
developing more robust safety mechanisms in T2I systems.
