---
layout: publication
title: 'RBF++: Quantifying And Optimizing Reasoning Boundaries Across Measurable And Unmeasurable Capabilities For Chain-of-thought Reasoning'
authors: Qiguang Chen, Libo Qin, Jinhao Liu, Yue Liao, Jiaqi Wang, Jingxuan Zhou, Wanxiang Che
conference: "Arxiv"
year: 2025
bibkey: chen2025quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13307"}
  - {name: "Code", url: "https://github.com/LightChen233/reasoning-boundary"}
tags: ['Efficiency and Optimization', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Has Code', 'Applications']
---
Chain-of-Thought (CoT) reasoning has proven effective in enhancing large language models (LLMs) on complex tasks, spurring research into its underlying mechanisms. However, two primary challenges remain for real-world applications: (1) the lack of quantitative metrics and actionable guidelines for evaluating and optimizing measurable boundaries of CoT capability, and (2) the absence of methods to assess boundaries of unmeasurable CoT capability, such as multimodal perception. To address these gaps, we introduce the Reasoning Boundary Framework++ (RBF++). To tackle the first challenge, we define the reasoning boundary (RB) as the maximum limit of CoT performance. We also propose a combination law for RBs, enabling quantitative analysis and offering actionable guidance across various CoT tasks. For the second challenge, particularly in multimodal scenarios, we introduce a constant assumption, which replaces unmeasurable RBs with scenario-specific constants. Additionally, we propose the reasoning boundary division mechanism, which divides unmeasurable RBs into two sub-boundaries, facilitating the quantification and optimization of both unmeasurable domain knowledge and multimodal perception capabilities. Extensive experiments involving 38 models across 13 tasks validate the feasibility of our framework in cross-modal settings. Additionally, we evaluate 10 CoT strategies, offer insights into optimization and decay from two complementary perspectives, and expand evaluation benchmarks for measuring RBs in LLM reasoning. We hope this work advances the understanding of RBs and optimization strategies in LLMs. Code and data are available at https://github.com/LightChen233/reasoning-boundary.
