---
layout: publication
title: 'Navrag: Generating User Demand Instructions For Embodied Navigation Through Retrieval-augmented LLM'
authors: Zihan Wang, Yaohui Zhu, Gim Hee Lee, Yachun Fan
conference: "Arxiv"
year: 2025
bibkey: wang2025generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11142'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Vision-and-Language Navigation (VLN) is an essential skill for embodied
agents, allowing them to navigate in 3D environments following natural language
instructions. High-performance navigation models require a large amount of
training data, the high cost of manually annotating data has seriously hindered
this field. Therefore, some previous methods translate trajectory videos into
step-by-step instructions for expanding data, but such instructions do not
match well with users' communication styles that briefly describe destinations
or state specific needs. Moreover, local navigation trajectories overlook
global context and high-level task planning. To address these issues, we
propose NavRAG, a retrieval-augmented generation (RAG) framework that generates
user demand instructions for VLN. NavRAG leverages LLM to build a hierarchical
scene description tree for 3D scene understanding from global layout to local
details, then simulates various user roles with specific demands to retrieve
from the scene tree, generating diverse instructions with LLM. We annotate over
2 million navigation instructions across 861 scenes and evaluate the data
quality and navigation performance of trained models.
