---
layout: publication
title: 'Bias Similarity Across Large Language Models'
authors: Hyejun Jeong, Shiqing Ma, Amir Houmansadr
conference: "Arxiv"
year: 2024
bibkey: jeong2024bias
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12010"}
tags: ['Model Architecture', 'Fairness', 'Reinforcement Learning', 'Bias Mitigation', 'Ethics and Bias', 'Prompting', 'Applications']
---
Bias in Large Language Models remains a critical concern as these systems are increasingly deployed in high-stakes applications. Yet most fairness evaluations rely on scalar metrics or single-model analysis, overlooking how biases align -- or diverge -- across model families, scales, and tuning strategies. In this work, we reframe bias similarity as a form of functional similarity and evaluate 24 LLMs from four major families on over one million structured prompts spanning four bias dimensions. Our findings uncover that fairness is not strongly determined by model size, architecture, instruction tuning, or openness. Instead, bias behaviors are highly context-dependent and structurally persistent, often resistant to current alignment techniques. Contrary to common assumptions, we find that open-source models frequently match or outperform proprietary models in both fairness and utility. These results call into question the default reliance on proprietary systems and highlight the need for behaviorally grounded, model-specific audits to better understand how bias manifests and endures across the LLM landscape.
