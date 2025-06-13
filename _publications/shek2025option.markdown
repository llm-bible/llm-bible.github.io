---
layout: publication
title: 'Option Discovery Using Llm-guided Semantic Hierarchical Reinforcement Learning'
authors: Chak Lam Shek, Pratap Tokekar
conference: "Arxiv"
year: 2025
bibkey: shek2025option
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19007"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'RAG', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown remarkable promise in reasoning and
decision-making, yet their integration with Reinforcement Learning (RL) for
complex robotic tasks remains underexplored. In this paper, we propose an
LLM-guided hierarchical RL framework, termed LDSC, that leverages LLM-driven
subgoal selection and option reuse to enhance sample efficiency,
generalization, and multi-task adaptability. Traditional RL methods often
suffer from inefficient exploration and high computational cost. Hierarchical
RL helps with these challenges, but existing methods often fail to reuse
options effectively when faced with new tasks. To address these limitations, we
introduce a three-stage framework that uses LLMs for subgoal generation given
natural language description of the task, a reusable option learning and
selection method, and an action-level policy, enabling more effective
decision-making across diverse tasks. By incorporating LLMs for subgoal
prediction and policy guidance, our approach improves exploration efficiency
and enhances learning performance. On average, LDSC outperforms the baseline by
55.9% in average reward, demonstrating its effectiveness in complex RL
settings. More details and experiment videos could be found in
\href\{https://raaslab.org/projects/LDSC/\}\{this
link\footnote\{https://raaslab.org/projects/LDSC\}\}.
