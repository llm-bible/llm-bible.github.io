---
layout: publication
title: Re2llm Reflective Reinforcement Large Language Model For Session-based Recommendation
authors: Wang Ziyan, Du Yingpeng, Sun Zhu, Chua Haoyan, Feng Kaidong, Wang Wenya, Zhang Jie
conference: "Arxiv"
year: 2024
bibkey: wang2024reflective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16427"}
tags: ['Agentic', 'Fine Tuning', 'Merging', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) are emerging as promising approaches to enhance session-based recommendation (SBR) where both prompt-based and fine-tuning-based methods have been widely investigated to align LLMs with SBR. However the former methods struggle with optimal prompts to elicit the correct reasoning of LLMs due to the lack of task-specific feedback leading to unsatisfactory recommendations. Although the latter methods attempt to fine-tune LLMs with domain-specific knowledge they face limitations such as high computational costs and reliance on open-source backbones. To address such issues we propose a Reflective Reinforcement Large Language Model (Re2LLM) for SBR guiding LLMs to focus on specialized knowledge essential for more accurate recommendations effectively and efficiently. In particular we first design the Reflective Exploration Module to effectively extract knowledge that is readily understandable and digestible by LLMs. To be specific we direct LLMs to examine recommendation errors through self-reflection and construct a knowledge base (KB) comprising hints capable of rectifying these errors. To efficiently elicit the correct reasoning of LLMs we further devise the Reinforcement Utilization Module to train a lightweight retrieval agent. It learns to select hints from the constructed KB based on the task-specific feedback where the hints can serve as guidance to help correct LLMs reasoning for better recommendations. Extensive experiments on multiple real-world datasets demonstrate that our method consistently outperforms state-of-the-art methods.
