---
layout: publication
title: 'Embodiedrag: Dynamic 3D Scene Graph Retrieval For Efficient And Scalable Robot Task Planning'
authors: Meghan Booker, Grayson Byrd, Bethany Kemp, Aurora Schmidt, Corban Rivera
conference: "Arxiv"
year: 2024
bibkey: booker2024dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23968'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Ethics and Bias']
---
Recent advances in Large Language Models (LLMs) have helped facilitate
exciting progress for robotic planning in real, open-world environments. 3D
scene graphs (3DSGs) offer a promising environment representation for grounding
such LLM-based planners as they are compact and semantically rich. However, as
the robot's environment scales (e.g., number of entities tracked) and the
complexity of scene graph information increases (e.g., maintaining more
attributes), providing the 3DSG as-is to an LLM-based planner quickly becomes
infeasible due to input token count limits and attentional biases present in
LLMs. Inspired by the successes of Retrieval-Augmented Generation (RAG) methods
that retrieve query-relevant document chunks for LLM question and answering, we
adapt the paradigm for our embodied domain. Specifically, we propose a 3D scene
subgraph retrieval framework, called EmbodiedRAG, that we augment an LLM-based
planner with for executing natural language robotic tasks. Notably, our
retrieved subgraphs adapt to changes in the environment as well as changes in
task-relevancy as the robot executes its plan. We demonstrate EmbodiedRAG's
ability to significantly reduce input token counts (by an order of magnitude)
and planning time (up to 70% reduction in average time per planning step) while
improving success rates on AI2Thor simulated household tasks with a single-arm,
mobile manipulator. Additionally, we implement EmbodiedRAG on a quadruped with
a manipulator to highlight the performance benefits for robot deployment at the
edge in real environments.
