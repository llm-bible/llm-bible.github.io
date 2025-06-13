---
layout: publication
title: 'Badnaver: Exploring Jailbreak Attacks On Vision-and-language Navigation'
authors: Wenqi Lyu, Zerui Li, Yanyuan Qiao, Qi Wu
conference: "Arxiv"
year: 2025
bibkey: lyu2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12443"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Attention Mechanism', 'Multimodal Models', 'Prompting']
---
Multimodal large language models (MLLMs) have recently gained attention for their generalization and reasoning capabilities in Vision-and-Language Navigation (VLN) tasks, leading to the rise of MLLM-driven navigators. However, MLLMs are vulnerable to jailbreak attacks, where crafted prompts bypass safety mechanisms and trigger undesired outputs. In embodied scenarios, such vulnerabilities pose greater risks: unlike plain text models that generate toxic content, embodied agents may interpret malicious instructions as executable commands, potentially leading to real-world harm. In this paper, we present the first systematic jailbreak attack paradigm targeting MLLM-driven navigator. We propose a three-tiered attack framework and construct malicious queries across four intent categories, concatenated with standard navigation instructions. In the Matterport3D simulator, we evaluate navigation agents powered by five MLLMs and report an average attack success rate over 90%. To test real-world feasibility, we replicate the attack on a physical robot. Our results show that even well-crafted prompts can induce harmful actions and intents in MLLMs, posing risks beyond toxic output and potentially leading to physical harm.
