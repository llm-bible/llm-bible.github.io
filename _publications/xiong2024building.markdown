---
layout: publication
title: "Building Math Agents With Multi-turn Iterative Preference Learning"
authors: Xiong Wei, Shi Chengshuai, Shen Jiaming, Rosenberg Aviv, Qin Zhen, Calandriello Daniele, Khalman Misha, Joshi Rishabh, Piot Bilal, Saleh Mohammad, Jin Chi, Zhang Tong, Liu Tianqi
conference: "Arxiv"
year: 2024
bibkey: xiong2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02392"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent studies have shown that large language models (LLMs) mathematical problem-solving capabilities can be enhanced by integrating external tools such as code interpreters and employing multi-turn Chain-of-Thought (CoT) reasoning. While current methods focus on synthetic data generation and Supervised Fine-Tuning (SFT) this paper studies the complementary direct preference learning approach to further improve model performance. However existing direct preference learning algorithms are originally designed for the single-turn chat task and do not fully address the complexities of multi-turn reasoning and external tool integration required for tool-integrated mathematical reasoning tasks. To fill in this gap we introduce a multi-turn direct preference learning framework tailored for this context that leverages feedback from code interpreters and optimizes trajectory-level preferences. This framework includes multi-turn DPO and multi-turn KTO as specific implementations. The effectiveness of our framework is validated through training of various language models using an augmented prompt set from the GSM8K and MATH datasets. Our results demonstrate substantial improvements a supervised fine-tuned Gemma-1.1-it-7B models performance increased from 77.537; to 83.937; on GSM8K and from 46.137; to 51.237; on MATH. Similarly a Gemma-2-it-9B model improved from 84.137; to 86.337; on GSM8K and from 51.037; to 54.537; on MATH.
