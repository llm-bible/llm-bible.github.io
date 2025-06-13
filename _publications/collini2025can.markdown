---
layout: publication
title: 'Can Reasoning Models Reason About Hardware? An Agentic HLS Perspective'
authors: Luca Collini, Andrew Hennessee, Ramesh Karri, Siddharth Garg
conference: "Arxiv"
year: 2025
bibkey: collini2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12721"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'RAG', 'Fine-Tuning']
---
Recent Large Language Models (LLMs) such as OpenAI o3-mini and DeepSeek-R1
use enhanced reasoning through Chain-of-Thought (CoT). Their potential in
hardware design, which relies on expert-driven iterative optimization, remains
unexplored. This paper investigates whether reasoning LLMs can address
challenges in High-Level Synthesis (HLS) design space exploration and
optimization. During HLS, engineers manually define pragmas/directives to
balance performance and resource constraints. We propose an LLM-based
optimization agentic framework that automatically restructures code, inserts
pragmas, and identifies optimal design points via feedback from HLs tools and
access to integer-linear programming (ILP) solvers. Experiments compare
reasoning models against conventional LLMs on benchmarks using success rate,
efficiency, and design quality (area/latency) metrics, and provide the
first-ever glimpse into the CoTs produced by a powerful open-source reasoning
model like DeepSeek-R1.
