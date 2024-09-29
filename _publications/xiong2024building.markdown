---
layout: publication
title: Building Math Agents With Multi45;turn Iterative Preference Learning
authors: Xiong Wei, Shi Chengshuai, Shen Jiaming, Rosenberg Aviv, Qin Zhen, Calandriello Daniele, Khalman Misha, Joshi Rishabh, Piot Bilal, Saleh Mohammad, Jin Chi, Zhang Tong, Liu Tianqi
conference: "Arxiv"
year: 2024
bibkey: xiong2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02392"}
tags: ['Agentic', 'Fine Tuning', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent studies have shown that large language models (LLMs) mathematical problem45;solving capabilities can be enhanced by integrating external tools such as code interpreters and employing multi45;turn Chain45;of45;Thought (CoT) reasoning. While current methods focus on synthetic data generation and Supervised Fine45;Tuning (SFT) this paper studies the complementary direct preference learning approach to further improve model performance. However existing direct preference learning algorithms are originally designed for the single45;turn chat task and do not fully address the complexities of multi45;turn reasoning and external tool integration required for tool45;integrated mathematical reasoning tasks. To fill in this gap we introduce a multi45;turn direct preference learning framework tailored for this context that leverages feedback from code interpreters and optimizes trajectory45;level preferences. This framework includes multi45;turn DPO and multi45;turn KTO as specific implementations. The effectiveness of our framework is validated through training of various language models using an augmented prompt set from the GSM8K and MATH datasets. Our results demonstrate substantial improvements a supervised fine45;tuned Gemma45;1.145;it45;7B models performance increased from 77.537; to 83.937; on GSM8K and from 46.137; to 51.237; on MATH. Similarly a Gemma45;245;it45;9B model improved from 84.137; to 86.337; on GSM8K and from 51.037; to 54.537; on MATH.
