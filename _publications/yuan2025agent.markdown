---
layout: publication
title: 'Agent-r: Training Language Model Agents To Reflect Via Iterative Self-training'
authors: Siyu Yuan, Zehui Chen, Zhiheng Xi, Junjie Ye, Zhengyin Du, Jiecao Chen
conference: "Arxiv"
year: 2025
bibkey: yuan2025agent
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.11425'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Applications', 'Tools', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) agents are increasingly pivotal for addressing
complex tasks in interactive environments. Existing work mainly focuses on
enhancing performance through behavior cloning from stronger experts, yet such
approaches often falter in real-world applications, mainly due to the inability
to recover from errors. However, step-level critique data is difficult and
expensive to collect. Automating and dynamically constructing self-critique
datasets is thus crucial to empowering models with intelligent agent
capabilities. In this work, we propose an iterative self-training framework,
Agent-R, that enables language Agent to Reflect on the fly. Unlike traditional
methods that reward or penalize actions based on correctness, Agent-R leverages
MCTS to construct training data that recover correct trajectories from
erroneous ones. A key challenge of agent reflection lies in the necessity for
timely revision rather than waiting until the end of a rollout. To address
this, we introduce a model-guided critique construction mechanism: the actor
model identifies the first error step (within its current capability) in a
failed trajectory. Starting from it, we splice it with the adjacent correct
path, which shares the same parent node in the tree. This strategy enables the
model to learn reflection based on its current policy, therefore yielding
better learning efficiency. To further explore the scalability of this
self-improvement paradigm, we investigate iterative refinement of both error
correction capabilities and dataset construction. Our findings demonstrate that
Agent-R continuously improves the model's ability to recover from errors and
enables timely error correction. Experiments on three interactive environments
show that Agent-R effectively equips agents to correct erroneous actions while
avoiding loops, achieving superior performance compared to baseline methods
(+5.59%).
