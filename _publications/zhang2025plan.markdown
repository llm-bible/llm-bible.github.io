---
layout: publication
title: 'Plan-over-graph: Towards Parallelable LLM Agent Schedule'
authors: Shiqi Zhang, Xinbei Ma, Zouying Cao, Zhuosheng Zhang, Hai Zhao
conference: "Arxiv"
year: 2025
bibkey: zhang2025plan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14563"}
  - {name: "Code", url: "https://github.com/zsq259/Plan-over-Graph"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Large Language Models (LLMs) have demonstrated exceptional abilities in
reasoning for task planning. However, challenges remain under-explored for
parallel schedules. This paper introduces a novel paradigm, plan-over-graph, in
which the model first decomposes a real-life textual task into executable
subtasks and constructs an abstract task graph. The model then understands this
task graph as input and generates a plan for parallel execution. To enhance the
planning capability of complex, scalable graphs, we design an automated and
controllable pipeline to generate synthetic graphs and propose a two-stage
training scheme. Experimental results show that our plan-over-graph method
significantly improves task performance on both API-based LLMs and trainable
open-sourced LLMs. By normalizing complex tasks as graphs, our method naturally
supports parallel execution, demonstrating global efficiency. The code and data
are available at https://github.com/zsq259/Plan-over-Graph.
