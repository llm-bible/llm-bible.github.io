---
layout: publication
title: 'Advancing And Benchmarking Personalized Tool Invocation For Llms'
authors: Xu Huang, Yuefeng Huang, Weiwen Liu, Xingshan Zeng, Yasheng Wang, Ruiming Tang, Hong Xie, Defu Lian
conference: "Arxiv"
year: 2025
bibkey: huang2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04072"}
  - {name: "Code", url: "https://github.com/hyfshadow/PTBench"}
tags: ['Tools', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Has Code']
---
Tool invocation is a crucial mechanism for extending the capabilities of
Large Language Models (LLMs) and has recently garnered significant attention.
It enables LLMs to solve complex problems through tool calls while accessing
up-to-date world knowledge. However, existing work primarily focuses on the
fundamental ability of LLMs to invoke tools for problem-solving, without
considering personalized constraints in tool invocation. In this work, we
introduce the concept of Personalized Tool Invocation and define two key tasks:
Tool Preference and Profile-dependent Query. Tool Preference addresses user
preferences when selecting among functionally similar tools, while
Profile-dependent Query considers cases where a user query lacks certain tool
parameters, requiring the model to infer them from the user profile. To tackle
these challenges, we propose PTool, a data synthesis framework designed for
personalized tool invocation. Additionally, we construct \textbf\{PTBench\}, the
first benchmark for evaluating personalized tool invocation. We then fine-tune
various open-source models, demonstrating the effectiveness of our framework
and providing valuable insights. Our benchmark is public at
https://github.com/hyfshadow/PTBench.
