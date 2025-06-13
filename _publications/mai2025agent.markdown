---
layout: publication
title: 'Agent RL Scaling Law: Agent RL With Spontaneous Code Execution For Mathematical Problem Solving'
authors: Xinji Mai, Haotian Xu, Xing W, Weinong Wang, Yingying Zhang, Wenqiang Zhang
conference: "Arxiv"
year: 2025
bibkey: mai2025agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07773"}
  - {name: "Code", url: "https://github.com/yyht/openrlhf_async_pipline}{https://github.com/yyht/openrlhf\_async\_pipline"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code']
---
Large Language Models (LLMs) often struggle with mathematical reasoning tasks requiring precise, verifiable computation. While Reinforcement Learning (RL) from outcome-based rewards enhances text-based reasoning, understanding how agents autonomously learn to leverage external tools like code execution remains crucial. We investigate RL from outcome-based rewards for Tool-Integrated Reasoning, ZeroTIR, training base LLMs to spontaneously generate and execute Python code for mathematical problems without supervised tool-use examples. Our central contribution is we demonstrate that as RL training progresses, key metrics scale predictably. Specifically, we observe strong positive correlations where increased training steps lead to increases in the spontaneous code execution frequency, the average response length, and, critically, the final task accuracy. This suggests a quantifiable relationship between computational effort invested in training and the emergence of effective, tool-augmented reasoning strategies. We implement a robust framework featuring a decoupled code execution environment and validate our findings across standard RL algorithms and frameworks. Experiments show ZeroTIR significantly surpasses non-tool ZeroRL baselines on challenging math benchmarks. Our findings provide a foundational understanding of how autonomous tool use is acquired and scales within Agent RL, offering a reproducible benchmark for future studies. Code is released at \href\{https://github.com/yyht/openrlhf_async_pipline\}\{https://github.com/yyht/openrlhf\_async\_pipline\}.
