---
layout: publication
title: 'Agent Q: Advanced Reasoning And Learning For Autonomous AI Agents'
authors: Pranav Putta, Edmund Mills, Naman Garg, Sumeet Motwani, Chelsea Finn, Divyansh Garg, Rafael Rafailov
conference: "Arxiv"
year: 2024
bibkey: putta2024agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07199"}
tags: ['Fine-Tuning', 'Pre-Training', 'Agentic', 'Efficiency and Optimization', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Agent', 'Pretraining Methods']
---
Large Language Models (LLMs) have shown remarkable capabilities in natural
language tasks requiring complex reasoning, yet their application in agentic,
multi-step reasoning within interactive environments remains a difficult
challenge. Traditional supervised pre-training on static datasets falls short
in enabling autonomous agent capabilities needed to perform complex
decision-making in dynamic settings like web navigation. Previous attempts to
bridge this ga-through supervised fine-tuning on curated expert
demonstrations-often suffer from compounding errors and limited exploration
data, resulting in sub-optimal policy outcomes. To overcome these challenges,
we propose a framework that combines guided Monte Carlo Tree Search (MCTS)
search with a self-critique mechanism and iterative fine-tuning on agent
interactions using an off-policy variant of the Direct Preference Optimization
(DPO) algorithm. Our method allows LLM agents to learn effectively from both
successful and unsuccessful trajectories, thereby improving their
generalization in complex, multi-step reasoning tasks. We validate our approach
in the WebShop environment-a simulated e-commerce platform where it
consistently outperforms behavior cloning and reinforced fine-tuning baseline,
and beats average human performance when equipped with the capability to do
online search. In real-world booking scenarios, our methodology boosts Llama-3
70B model's zero-shot performance from 18.6% to 81.7% success rate (a 340%
relative increase) after a single day of data collection and further to 95.4%
with online search. We believe this represents a substantial leap forward in
the capabilities of autonomous agents, paving the way for more sophisticated
and reliable decision-making in real-world settings.
