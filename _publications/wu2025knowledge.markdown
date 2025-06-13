---
layout: publication
title: 'Knowledge Or Reasoning? A Close Look At How Llms Think Across Domains'
authors: Juncheng Wu, Sheng Liu, Haoqin Tu, Hang Yu, Xiaoke Huang, James Zou, Cihang Xie, Yuyin Zhou
conference: "Arxiv"
year: 2025
bibkey: wu2025knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02126'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pruning', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Pretraining Methods']
---
Recent advances in reasoning-enhanced Large Language Models such as OpenAI-o1/3 and DeepSeek-R1 have significantly improved performance on complex tasks. However, the quality and transparency of their internal reasoning processes remain underexplored. This work moves beyond the final-answer accuracy and investigates step-by-step reasoning in the medical and mathematical domains by explicitly decomposing the thinking trajectories into two parts: knowledge and reasoning. Specifically, we introduce a fine-grained evaluation framework that judges: (1) the correctness of knowledge used (measured by Knowledge Index (KI)) and (2) the quality of reasoning (measured by Information Gain (InfoGain)). Using this framework, we study R1-distilled and base Qwen models trained with supervised fine-tuning (SFT) and/or reinforcement learning (RL) in the medical and math domains. Three intriguing findings emerge: (1) The general reasoning abilities in R1-distilled models do not transfer effectively to the medical domain through either SFT or RL. (2) SFT raises final-answer accuracy in both domains, but often at the cost of reasoning quality: InfoGain drops by 38.9% on average compared with untrained models; In the medical domain, however, SFT remains crucial because domain knowledge is indispensable. (3) RL enhances medical reasoning by pruning inaccurate or irrelevant knowledge from reasoning paths, thereby improving both reasoning accuracy and knowledge correctness.
