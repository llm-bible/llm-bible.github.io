---
layout: publication
title: 'Rag-reward: Optimizing RAG With Reward Modeling And RLHF'
authors: Hanning Zhang, Juntong Song, Juno Zhu, Yuanhao Wu, Tong Zhang, Cheng Niu
conference: "Arxiv"
year: 2025
bibkey: zhang2025rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13264"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'RAG', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) enhances Large Language Models (LLMs)
with relevant and up-to-date knowledge, improving their ability to answer
knowledge-intensive questions. It has been shown to enhance both generation
quality and trustworthiness. While numerous works have focused on improving
retrieval, generation, and evaluation, the role of reward models in
reinforcement learning for optimizing RAG remains underexplored. In this paper,
we introduce \textbf\{RAG-Reward\}, a framework designed to develop reward models
to enable \textit\{hallucination-free, comprehensive, reliable, and efficient
RAG\}. We define four key metrics to assess generation quality and develop an
automated benchmarking pipeline to evaluate the outputs of multiple LLMs across
a variety of RAG scenarios. Using \textbf\{RAG-Reward\}, we train reward models
and apply \{reinforcement learning with human feedback (RLHF)\} to improve LLMs'
effectiveness in RAG. Experimental results demonstrate that our reward model
achieves state-of-the-art performance in automatic benchmarking and aligns
closely with human evaluations. Furthermore, the improved generation quality of
the trained policy model highlights the feasibility and efficiency of using
RLHF to enhance RAG outputs.
