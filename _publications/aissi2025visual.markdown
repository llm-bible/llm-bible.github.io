---
layout: publication
title: 'VIPER: Visual Perception And Explainable Reasoning For Sequential Decision-making'
authors: Mohamed Salim Aissi, Clemence Grislain, Mohamed Chetouani, Olivier Sigaud, Laure Soulier, Nicolas Thome
conference: "Arxiv"
year: 2025
bibkey: aissi2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15108"}
tags: ['Agentic', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Interpretability', 'ACL', 'Interpretability and Explainability']
---
While Large Language Models (LLMs) excel at reasoning on text and
Vision-Language Models (VLMs) are highly effective for visual perception,
applying those models for visual instruction-based planning remains a widely
open problem. In this paper, we introduce VIPER, a novel framework for
multimodal instruction-based planning that integrates VLM-based perception with
LLM-based reasoning. Our approach uses a modular pipeline where a frozen VLM
generates textual descriptions of image observations, which are then processed
by an LLM policy to predict actions based on the task goal. We fine-tune the
reasoning module using behavioral cloning and reinforcement learning, improving
our agent's decision-making capabilities. Experiments on the ALFWorld benchmark
show that VIPER significantly outperforms state-of-the-art visual
instruction-based planners while narrowing the gap with purely text-based
oracles. By leveraging text as an intermediate representation, VIPER also
enhances explainability, paving the way for a fine-grained analysis of
perception and reasoning components.
