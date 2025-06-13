---
layout: publication
title: 'Dr. Sow: Density Ratio Of Strong-over-weak Llms For Reducing The Cost Of Human Annotation In Preference Tuning'
authors: Guangxuan Xu, Kai Xu, Shivchander Sudalairaj, Hao Wang, Akash Srivastava
conference: "Arxiv"
year: 2024
bibkey: xu2024density
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02481"}
tags: ['Responsible AI', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Preference tuning relies on high-quality human preference data, which is
often expensive and time-consuming to gather. In this paper, we introduce
Dr.SoW (Density Ratio of Strong over Weak) a cost-effective method that
eliminates the reliance for human annotation by leveraging off-the-shelf LLMs
for preference data annotation. Dr.SoW uses the log-density ratio between a
better-aligned and a less-aligned LLM as a reward signal. We evaluate Dr.SoW
across 221 different LLM pairs and empirically find a strong correlation
between the performance gap of the paired models and the quality of the reward
signal. This insight provides a practical guideline for selecting LLMs for data
annotation.
  Additionally, we introduce an end-to-end pipeline that customizes reward
functions based on user query domains. Without fine-tuning, it improves
accuracy on domain-specific evaluations. With a pair of Mistral-7B models,
Dr.SoW achieves a RewardBench score of 82.6, outperforming the best trained
reward functions from same model class and demonstrating competitive
performance against SoTA models in Safety (91.0) and Reasoning (88.0) domains.
Further, we preference-tune Llama-3-8B-Instruct using data annotated by Dr.SoW.
Our approach pushes Llama-3-8B to achieve a 37.4 % (+15.1 %) win rate on
ArenaHard and a 40.7 % (+17.8 %) win rate on length-controlled AlpacaEval 2.0.
