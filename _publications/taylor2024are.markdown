---
layout: publication
title: 'Are Large-language Models Graph Algorithmic Reasoners?'
authors: Alexander K Taylor, Anthony Cuturrufo, Vishal Yathish, Mingyu Derek Ma, Wei Wang
conference: "Arxiv"
year: 2024
bibkey: taylor2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22597"}
tags: ['Prompting']
---
We seek to address a core challenge facing current Large Language Models
(LLMs). LLMs have demonstrated superior performance in many tasks, yet continue
to struggle with reasoning problems on explicit graphs that require multiple
steps. To address this gap, we introduce a novel benchmark designed to evaluate
LLM performance on classical algorithmic reasoning tasks on explicit graphs.
Our benchmark encompasses five fundamental algorithms: Breadth-First Search
(BFS) and Depth-First Search (DFS) for connectivity, Dijkstra's algorithm and
Floyd-Warshall algorithm for all nodes shortest path, and Prim's Minimum
Spanning Tree (MST-Prim's) algorithm. Through extensive experimentation, we
assess the capabilities of state-of-the-art LLMs in executing these algorithms
step-by-step and systematically evaluate their performance at each stage. Our
findings highlight the persistent challenges LLMs face in this domain and
underscore the necessity for advanced prompting techniques and algorithmic
instruction to enhance their graph reasoning abilities. This work presents
MAGMA, the first comprehensive benchmark focused on LLMs completing classical
graph algorithms, and provides a critical step toward understanding and
improving their structured problem-solving skills.
