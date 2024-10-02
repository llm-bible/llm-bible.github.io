---
layout: publication
title: 'Preference-guided Reflective Sampling For Aligning Language Models'
authors: Ye Hai, Ng Hwee Tou
conference: "Arxiv"
year: 2024
bibkey: ye2024preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12163"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Language Modeling', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) are aligned with human preferences by reinforcement learning from human feedback (RLHF). Effective data sampling is crucial for RLHF, as it determines the efficiency of model training, ensuring that models learn from the informative samples. To achieve better data generation, we propose a new sampling method called Preference-Guided Reflective Sampling (PRS). PRS frames the response generation as an optimization process to the explicitly specified user preference described in natural language. It employs a tree-based generation framework to enable an efficient sampling process, which guides the direction of generation through preference and better explores the sampling space with adaptive self-refinement. Notably, PRS can align LLMs to diverse preferences. We study preference-controlled text generation for instruction following and keyword-focused document summarization. Our findings indicate that PRS, across different LLM policies, generates training data with much higher rewards than strong baselines. PRS also excels in post-RL training.
