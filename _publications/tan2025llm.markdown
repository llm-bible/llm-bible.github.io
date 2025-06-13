---
layout: publication
title: 'Llm-guided Reinforcement Learning: Addressing Training Bottlenecks Through Policy Modulation'
authors: Heng Tan, Hua Yan, Yu Yang
conference: "Arxiv"
year: 2025
bibkey: tan2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20671'}
tags: ['Agentic', 'Interpretability and Explainability', 'RAG', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
While reinforcement learning (RL) has achieved notable success in various domains, training effective policies for complex tasks remains challenging. Agents often converge to local optima and fail to maximize long-term rewards. Existing approaches to mitigate training bottlenecks typically fall into two categories: (i) Automated policy refinement, which identifies critical states from past trajectories to guide policy updates, but suffers from costly and uncertain model training; and (ii) Human-in-the-loop refinement, where human feedback is used to correct agent behavior, but this does not scale well to environments with large or continuous action spaces. In this work, we design a large language model-guided policy modulation framework that leverages LLMs to improve RL training without additional model training or human intervention. We first prompt an LLM to identify critical states from a sub-optimal agent's trajectories. Based on these states, the LLM then provides action suggestions and assigns implicit rewards to guide policy refinement. Experiments across standard RL benchmarks demonstrate that our method outperforms state-of-the-art baselines, highlighting the effectiveness of LLM-based explanations in addressing RL training bottlenecks.
