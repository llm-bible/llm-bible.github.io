---
layout: publication
title: 'Rag-modulo: Solving Sequential Tasks Using Experience, Critics, And Language Models'
authors: Abhinav Jain, Chris Jermaine, Vaibhav Unhelkar
conference: "Arxiv"
year: 2024
bibkey: jain2024rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12294"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG']
---
Large language models (LLMs) have recently emerged as promising tools for
solving challenging robotic tasks, even in the presence of action and
observation uncertainties. Recent LLM-based decision-making methods (also
referred to as LLM-based agents), when paired with appropriate critics, have
demonstrated potential in solving complex, long-horizon tasks with relatively
few interactions. However, most existing LLM-based agents lack the ability to
retain and learn from past interactions - an essential trait of learning-based
robotic systems. We propose RAG-Modulo, a framework that enhances LLM-based
agents with a memory of past interactions and incorporates critics to evaluate
the agents' decisions. The memory component allows the agent to automatically
retrieve and incorporate relevant past experiences as in-context examples,
providing context-aware feedback for more informed decision-making. Further by
updating its memory, the agent improves its performance over time, thereby
exhibiting learning. Through experiments in the challenging BabyAI and AlfWorld
domains, we demonstrate significant improvements in task success rates and
efficiency, showing that the proposed RAG-Modulo framework outperforms
state-of-the-art baselines.
