---
layout: publication
title: 'KAQG: A Knowledge-graph-enhanced RAG For Difficulty-controlled Question Generation'
authors: Ching Han Chen, Ming Fang Shiu
conference: "Arxiv"
year: 2025
bibkey: chen2025knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07618"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning']
---
KAQG introduces a decisive breakthrough for Retrieval-Augmented Generation (RAG) by explicitly tackling the two chronic weaknesses of current pipelines: transparent multi-step reasoning and fine-grained cognitive difficulty control. This transforms RAG from a passive retriever into an accountable generator of calibrated exam items. Technically, the framework fuses knowledge graphs, RAG retrieval, and educational assessment theory into a single pipeline. Domain passages are parsed into a structured graph; graph-aware retrieval feeds fact chains to an LLM; and an assessment layer governed by Bloom's Taxonomy levels and Item Response Theory (IRT) transforms those chains into psychometrically sound questions. This cross-disciplinary marriage yields two scholarly contributions: it shows how semantic graph contexts guide LLM reasoning paths, and it operationalizes difficulty metrics within the generation process, producing items whose IRT parameters match expert benchmarks. Every module, from KG construction scripts to the multi-agent reasoning scheduler and the automatic IRT validator, is openly released on GitHub. This enables peer laboratories to replicate experiments, benchmark against baselines, and extend individual components without licensing barriers. Its reproducible design paves the way for rigorous ablation studies, cross-domain transfer experiments, and shared leaderboards on multi-step reasoning benchmarks.
