---
layout: publication
title: 'Exploring Expert Failures Improves LLM Agent Tuning'
authors: Li-cheng Lan, Andrew Bai, Minhao Cheng, Cho-jui Hsieh, Tianyi Zhou
conference: "Arxiv"
year: 2025
bibkey: lan2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13145"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Large Language Models (LLMs) have shown tremendous potential as agents,
excelling at tasks that require multiple rounds of reasoning and interactions.
Rejection Sampling Fine-Tuning (RFT) has emerged as an effective method for
finetuning LLMs as agents: it first imitates expert-generated successful
trajectories and further improves agentic skills through iterative fine-tuning
on successful, self-generated trajectories. However, since the expert (e.g.,
GPT-4) succeeds primarily on simpler subtasks and RFT inherently favors simpler
scenarios, many complex subtasks remain unsolved and persistently
out-of-distribution (OOD). Upon investigating these challenging subtasks, we
discovered that previously failed expert trajectories can often provide
valuable guidance, e.g., plans and key actions, that can significantly improve
agent exploration efficiency and acquisition of critical skills. Motivated by
these observations, we propose Exploring Expert Failures (EEF), which
identifies beneficial actions from failed expert trajectories and integrates
them into the training dataset. Potentially harmful actions are meticulously
excluded to prevent contamination of the model learning process. By leveraging
the beneficial actions in expert failures, EEF successfully solves some
previously unsolvable subtasks and improves agent tuning performance.
Remarkably, our approach achieved a 62% win rate in WebShop, outperforming RFT
(53. 6%) and GPT-4 (35. 6%), and to the best of our knowledge, setting a new
state-of-the-art as the first method to surpass a score of 0.81 in WebShop and
exceed 81 in SciWorld.
