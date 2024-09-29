---
layout: publication
title: Empowering Large Language Model Agents Through Action Learning
authors: Zhao Haiteng, Ma Chang, Wang Guoyin, Su Jing, Kong Lingpeng, Xu Jingjing, Deng Zhi-hong, Yang Hongxia
conference: "Arxiv"
year: 2024
bibkey: zhao2024empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15809"}
tags: ['Agentic', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Model (LLM) Agents have recently garnered increasing interest yet they are limited in their ability to learn from trial and error a key element of intelligent behavior. In this work we argue that the capacity to learn new actions from experience is fundamental to the advancement of learning in LLM agents. While humans naturally expand their action spaces and develop skills through experiential learning LLM agents typically operate within fixed action spaces limiting their potential for growth. To address these challenges our study explores open-action learning for language agents. We introduce a framework LearnAct with an iterative learning strategy to create and improve actions in the form of Python functions. In each iteration LLM revises and updates the currently available actions based on the errors identified in unsuccessful training tasks thereby enhancing action effectiveness. Our experimental evaluations across Robotic Planning and Alfworld environments reveal that after learning on a few training task instances our approach to open-action learning markedly improves agent performance for the type of task (by 32 percent in AlfWorld compared to ReAct+Reflexion for instance) highlighting the importance of experiential action learning in the development of more intelligent LLM agents.
