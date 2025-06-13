---
layout: publication
title: 'Addressing The Challenges Of Planning Language Generation'
authors: Prabhu Prakash Kagitha, Andrew Zhu, Li Zhang
conference: "Arxiv"
year: 2025
bibkey: kagitha2025addressing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14763'}
tags: ['Uncategorized']
---
Using LLMs to generate formal planning languages such as PDDL that invokes symbolic solvers to deterministically derive plans has been shown to outperform generating plans directly. While this success has been limited to closed-sourced models or particular LLM pipelines, we design and evaluate 8 different PDDL generation pipelines with open-source models under 50 billion parameters previously shown to be incapable of this task. We find that intuitive approaches such as using a high-resource language wrapper or constrained decoding with grammar decrease performance, yet inference-time scaling approaches such as revision with feedback from the solver and plan validator more than double the performance.
