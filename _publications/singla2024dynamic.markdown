---
layout: publication
title: 'Dynamic Rewarding With Prompt Optimization Enables Tuning-free Self-alignment Of Language Models'
authors: Somanshu Singla, Zhen Wang, Tianyang Liu, Abdullah Ashfaq, Zhiting Hu, Eric P. Xing
conference: "Arxiv"
year: 2024
bibkey: singla2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.08733"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Aligning Large Language Models (LLMs) traditionally relies on costly training
and human preference annotations. Self-alignment seeks to reduce these expenses
by enabling models to align themselves. To further lower costs and achieve
alignment without any expensive tuning or annotations, we introduce a new
tuning-free approach for self-alignment, Dynamic Rewarding with Prompt
Optimization (DRPO). Our approach leverages a search-based optimization
framework that allows LLMs to iteratively self-improve and craft the optimal
alignment instructions, all without additional training or human intervention.
The core of DRPO is a dynamic rewarding mechanism, which identifies and
rectifies model-specific alignment weaknesses, allowing LLMs to adapt
efficiently to diverse alignment challenges. Empirical evaluations on eight
recent LLMs, both open- and closed-sourced, demonstrate that DRPO significantly
enhances alignment performance, with base models outperforming their
SFT/RLHF-tuned counterparts. Moreover, the prompts automatically optimized by
DRPO surpass those curated by human experts, further validating the
effectiveness of our approach. Our findings highlight the great potential of
current LLMs to achieve adaptive self-alignment through inference-time
optimization, complementing tuning-based alignment methods.
