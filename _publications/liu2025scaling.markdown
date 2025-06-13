---
layout: publication
title: 'Scaling External Knowledge Input Beyond Context Windows Of Llms Via Multi-agent Collaboration'
authors: Zijun Liu, Zhennan Wan, Peng Li, Ming Yan, Ji Zhang, Fei Huang, Yang Liu
conference: "Arxiv"
year: 2025
bibkey: liu2025scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21471'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Tools', 'Survey Paper', 'Reinforcement Learning']
---
With the rapid advancement of post-training techniques for reasoning and information seeking, large language models (LLMs) can incorporate a large quantity of retrieved knowledge to solve complex tasks. However, the limited context window of LLMs obstructs scaling the amount of external knowledge input, prohibiting further improvement, especially for tasks requiring significant amount of external knowledge. Existing context window extension methods inevitably cause information loss. LLM-based multi-agent methods emerge as a new paradigm to handle massive input in a distributional manner, where we identify two core bottlenecks in existing knowledge synchronization and reasoning processes. In this work, we develop a multi-agent framework, \\(\textbf\{ExtAgents\}\\), to overcome the bottlenecks and enable better scalability in inference-time knowledge integration without longer-context training. Benchmarked with our enhanced multi-hop question answering test, \\(\textbf\{\\)\boldsymbol\{\infty\}\\(Bench+\}\\), and other public test sets including long survey generation, ExtAgents significantly enhances the performance over existing non-training methods with the same amount of external knowledge input, regardless of whether it falls \\(\textit\{within or exceeds the context window\}\\). Moreover, the method maintains high efficiency due to high parallelism. Further study in the coordination of LLM agents on increasing external knowledge input could benefit real-world applications.
