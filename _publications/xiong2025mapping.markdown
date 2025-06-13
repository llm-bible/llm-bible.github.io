---
layout: publication
title: 'Mapping The Minds Of Llms: A Graph-based Analysis Of Reasoning LLM'
authors: Zhen Xiong, Yujun Cai, Zhecheng Li, Yiwei Wang
conference: "Arxiv"
year: 2025
bibkey: xiong2025mapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13890"}
tags: ['Few-Shot', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Recent advances in test-time scaling have enabled Large Language Models (LLMs) to display sophisticated reasoning abilities via extended Chain-of-Thought (CoT) generation. Despite their potential, these Reasoning LLMs (RLMs) often demonstrate counterintuitive and unstable behaviors, such as performance degradation under few-shot prompting, that challenge our current understanding of RLMs. In this work, we introduce a unified graph-based analytical framework for better modeling the reasoning processes of RLMs. Our method first clusters long, verbose CoT outputs into semantically coherent reasoning steps, then constructs directed reasoning graphs to capture contextual and logical dependencies among these steps. Through comprehensive analysis across models and prompting regimes, we reveal that structural properties, such as exploration density, branching, and convergence ratios, strongly correlate with reasoning accuracy. Our findings demonstrate how prompting strategies substantially reshape the internal reasoning structure of RLMs, directly affecting task outcomes. The proposed framework not only enables quantitative evaluation of reasoning quality beyond conventional metrics but also provides practical insights for prompt engineering and the cognitive analysis of LLMs. Code and resources will be released to facilitate future research in this direction.
