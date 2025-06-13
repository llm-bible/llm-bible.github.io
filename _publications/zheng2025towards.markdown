---
layout: publication
title: 'Deeprec: Towards A Deep Dive Into The Item Space With Large Language Model Based Recommendation'
authors: Bowen Zheng, Xiaolei Wang, Enze Liu, Xi Wang, Lu Hongyu, Yu Chen, Wayne Xin Zhao, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: zheng2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16810"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RecSys', 'Fine-Tuning']
---
Recently, large language models (LLMs) have been introduced into recommender systems (RSs), either to enhance traditional recommendation models (TRMs) or serve as recommendation backbones. However, existing LLM-based RSs often do not fully exploit the complementary advantages of LLMs (e.g., world knowledge and reasoning) and TRMs (e.g., recommendation-specific knowledge and efficiency) to fully explore the item space. To address this, we propose DeepRec, a novel LLM-based RS that enables autonomous multi-turn interactions between LLMs and TRMs for deep exploration of the item space. In each interaction turn, LLMs reason over user preferences and interact with TRMs to retrieve candidate items. After multi-turn interactions, LLMs rank the retrieved items to generate the final recommendations. We adopt reinforcement learning(RL) based optimization and propose novel designs from three aspects: recommendation model based data rollout, recommendation-oriented hierarchical rewards, and a two-stage RL training strategy. For data rollout, we introduce a preference-aware TRM, with which LLMs interact to construct trajectory data. For rewards, we design a hierarchical reward function that involves both process-level and outcome-level rewards to optimize the interaction process and recommendation performance, respectively. For RL training, we develop a two-stage training strategy, where the first stage aims to guide LLMs to interact with TRMs and the second stage focuses on performance improvement. Experiments on public datasets demonstrate that DeepRec significantly outperforms both traditional and LLM-based baselines, offering a new paradigm for deep exploration in recommendation systems.
