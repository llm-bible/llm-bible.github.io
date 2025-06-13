---
layout: publication
title: 'Adaptive Deep Reasoning: Triggering Deep Thinking When Needed'
authors: Yunhao Wang, Yuhao Zhang, Tinghao Yu, Can Xu, Feng Zhang, Fengzong Lian
conference: "Arxiv"
year: 2025
bibkey: wang2025adaptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20101'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have shown impressive capabilities in handling complex tasks through long-chain reasoning. However, the extensive reasoning steps involved can significantly increase computational costs, posing challenges for real-world deployment. Recent efforts have focused on optimizing reasoning efficiency by shortening the Chain-of-Thought (CoT) reasoning processes through various approaches, such as length-aware prompt engineering, supervised fine-tuning on CoT data with variable lengths, and reinforcement learning with length penalties. Although these methods effectively reduce reasoning length, they still necessitate an initial reasoning phase. More recent approaches have attempted to integrate long-chain and short-chain reasoning abilities into a single model, yet they still rely on manual control to toggle between short and long CoT. In this work, we propose a novel approach that autonomously switches between short and long reasoning chains based on problem complexity. Our method begins with supervised fine-tuning of the base model to equip both long-chain and short-chain reasoning abilities. We then employ reinforcement learning to further balance short and long CoT generation while maintaining accuracy through two key strategies: first, integrating reinforcement learning with a long-short adaptive group-wise reward strategy to assess prompt complexity and provide corresponding rewards; second, implementing a logit-based reasoning mode switching loss to optimize the model's initial token choice, thereby guiding the selection of the reasoning type. Evaluations on mathematical datasets demonstrate that our model can dynamically switch between long-chain and short-chain reasoning modes without substantially sacrificing performance. This advancement enhances the practicality of reasoning in large language models for real-world applications.
