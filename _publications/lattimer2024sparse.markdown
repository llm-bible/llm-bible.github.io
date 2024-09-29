---
layout: publication
title: "Sparse Rewards Can Self-train Dialogue Agents"
authors: Lattimer Barrett Martin, Gangal Varun, Mcdonald Ryan, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: lattimer2024sparse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04617"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recent advancements in state-of-the-art (SOTA) Large Language Model (LLM) agents especially in multi-turn dialogue tasks have been primarily driven by supervised fine-tuning and high-quality human feedback. However as base LLM models continue to improve acquiring meaningful human feedback has become increasingly challenging and costly. In certain domains base LLM agents may eventually exceed human capabilities making traditional feedback-driven methods impractical. In this paper we introduce a novel self-improvement paradigm that empowers LLM agents to autonomously enhance their performance without external human feedback. Our method Juxtaposed Outcomes for Simulation Harvesting (JOSH) is a self-alignment algorithm that leverages a sparse reward simulation environment to extract ideal behaviors and further train the LLM on its own outputs. We present ToolWOZ a sparse reward tool-calling simulation environment derived from MultiWOZ. We demonstrate that models trained with JOSH both small and frontier significantly improve tool-based interactions while preserving general model capabilities across diverse benchmarks. Our code and data are publicly available on GitHub.
