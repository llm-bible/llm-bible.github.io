---
layout: publication
title: 'Lightplanner: Unleashing The Reasoning Capabilities Of Lightweight Large Language Models In Task Planning'
authors: Weijie Zhou, Yi Peng, Manli Tao, Chaoyang Zhao, Honghui Dong, Ming Tang, Jinqiao Wang
conference: "Arxiv"
year: 2025
bibkey: zhou2025unleashing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08508'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning']
---
In recent years, lightweight large language models (LLMs) have garnered
significant attention in the robotics field due to their low computational
resource requirements and suitability for edge deployment. However, in task
planning -- particularly for complex tasks that involve dynamic semantic logic
reasoning -- lightweight LLMs have underperformed. To address this limitation,
we propose a novel task planner, LightPlanner, which enhances the performance
of lightweight LLMs in complex task planning by fully leveraging their
reasoning capabilities. Unlike conventional planners that use fixed skill
templates, LightPlanner controls robot actions via parameterized function
calls, dynamically generating parameter values. This approach allows for
fine-grained skill control and improves task planning success rates in complex
scenarios. Furthermore, we introduce hierarchical deep reasoning. Before
generating each action decision step, LightPlanner thoroughly considers three
levels: action execution (feedback verification), semantic parsing (goal
consistency verification), and parameter generation (parameter validity
verification). This ensures the correctness of subsequent action controls.
Additionally, we incorporate a memory module to store historical actions,
thereby reducing context length and enhancing planning efficiency for long-term
tasks. We train the LightPlanner-1.5B model on our LightPlan-40k dataset, which
comprises 40,000 action controls across tasks with 2 to 13 action steps.
Experiments demonstrate that our model achieves the highest task success rate
despite having the smallest number of parameters. In tasks involving spatial
semantic reasoning, the success rate exceeds that of ReAct by 14.9 percent.
Moreover, we demonstrate LightPlanner's potential to operate on edge devices.
