---
layout: publication
title: Role Prompting Guided Domain Adaptation With General Capability Preserve For Large Language Models
authors: Wang Rui, Mi Fei, Chen Yi, Xue Boyang, Wang Hongru, Zhu Qi, Wong Kam-fai, Xu Ruifeng
conference: "Arxiv"
year: 2024
bibkey: wang2024role
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02756"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Merging', 'Prompting', 'Training Techniques']
---
The growing interest in Large Language Models (LLMs) for specialized applications has revealed a significant challenge when tailored to specific domains LLMs tend to experience catastrophic forgetting compromising their general capabilities and leading to a suboptimal user experience. Additionally crafting a versatile model for multiple domains simultaneously often results in a decline in overall performance due to confusion between domains. In response to these issues we present the RolE Prompting Guided Multi45;Domain Adaptation (REGA) strategy. This novel approach effectively manages multi45;domain LLM adaptation through three key components 1) Self45;Distillation constructs and replays general45;domain exemplars to alleviate catastrophic forgetting. 2) Role Prompting assigns a central prompt to the general domain and a unique role prompt to each specific domain to minimize inter45;domain confusion during training. 3) Role Integration reuses and integrates a small portion of domain45;specific data to the general45;domain data which are trained under the guidance of the central prompt. The central prompt is used for a streamlined inference process removing the necessity to switch prompts for different domains. Empirical results demonstrate that REGA effectively alleviates catastrophic forgetting and inter45;domain confusion. This leads to improved domain45;specific performance compared to standard fine45;tuned models while still preserving robust general capabilities.
