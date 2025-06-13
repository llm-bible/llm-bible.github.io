---
layout: publication
title: 'Vflow: Discovering Optimal Agentic Workflows For Verilog Generation'
authors: Yangbo Wei, Zhen Huang, Huang Li, Wei W. Xing, Ting-jung Lin, Lei He
conference: "Arxiv"
year: 2025
bibkey: wei2025discovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03723"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Applications', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Hardware design automation faces challenges in generating high-quality
Verilog code efficiently. This paper introduces VFlow, an automated framework
that optimizes agentic workflows for Verilog code generation. Unlike existing
approaches that rely on pre-defined prompting strategies, VFlow leverages Monte
Carlo Tree Search (MCTS) to discover effective sequences of Large Language
Models invocations that maximize code quality while minimizing computational
costs. VFlow extends the AFLOW methodology with domain-specific operators
addressing hardware design requirements, including syntax validation,
simulation-based verification, and synthesis optimization. Experimental
evaluation on the VerilogEval benchmark demonstrates VFlow's superiority,
achieving an 83.6% average pass@1 rate-a 6.1% improvement over
state-of-the-art PromptV and a 36.9% gain compared to direct LLM invocation.
Most significantly, VFlow enhances the capabilities of smaller models, enabling
DeepSeek-V3 to achieve 141.2% of GPT-4o's performance while reducing API costs
to just 13%. These findings indicate that intelligently optimized workflows
enable cost-efficient LLMs to outperform larger models on hardware design
tasks, potentially democratizing access to advanced digital circuit development
tools and accelerating innovation in the semiconductor industry
