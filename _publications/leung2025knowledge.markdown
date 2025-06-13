---
layout: publication
title: 'Knowledge Retrieval In LLM Gaming: A Shift From Entity-centric To Goal-oriented Graphs'
authors: Jonathan Leung, Yongjie Wang, Zhiqi Shen
conference: "Arxiv"
year: 2025
bibkey: leung2025knowledge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18607'}
tags: ['RAG', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) demonstrate impressive general capabilities but often struggle with step-by-step reasoning, especially in complex applications such as games. While retrieval-augmented methods like GraphRAG attempt to bridge this gap through cross-document extraction and indexing, their fragmented entity-relation graphs and overly dense local connectivity hinder the construction of coherent reasoning. In this paper, we propose a novel framework based on Goal-Oriented Graphs (GoGs), where each node represents a goal and its associated attributes, and edges encode logical dependencies between goals. This structure enables explicit retrieval of reasoning paths by first identifying high-level goals and recursively retrieving their subgoals, forming coherent reasoning chains to guide LLM prompting. Our method significantly enhances the reasoning ability of LLMs in game-playing tasks, as demonstrated by extensive experiments on the Minecraft testbed, outperforming GraphRAG and other baselines.
