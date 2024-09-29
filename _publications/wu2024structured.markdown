---
layout: publication
title: Agentkit&#58; Structured LLM Reasoning With Dynamic Graphs
authors: Wu Yue, Fan Yewen, Min So Yeon, Prabhumoye Shrimai, Mcaleer Stephen, Bisk Yonatan, Salakhutdinov Ruslan, Li Yuanzhi, Mitchell Tom
conference: "Arxiv"
year: 2024
bibkey: wu2024structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11483"}
  - {name: "Code", url: "https://github.com/holmeswww/AgentKit"}
tags: ['Agentic', 'Applications', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Tools']
---
We propose an intuitive LLM prompting framework (AgentKit) for multifunctional agents. AgentKit offers a unified framework for explicitly constructing a complex thought process from simple natural language prompts. The basic building block in AgentKit is a node containing a natural language prompt for a specific subtask. The user then puts together chains of nodes like stacking LEGO pieces. The chains of nodes can be designed to explicitly enforce a naturally structured thought process. For example for the task of writing a paper one may start with the thought process of 1) identify a core message 2) identify prior research gaps etc. The nodes in AgentKit can be designed and combined in different ways to implement multiple advanced capabilities including on-the-fly hierarchical planning reflection and learning from interactions. In addition due to the modular nature and the intuitive design to simulate explicit human thought process a basic agent could be implemented as simple as a list of prompts for the subtasks and therefore could be designed and tuned by someone without any programming experience. Quantitatively we show that agents designed through AgentKit achieve SOTA performance on WebShop and Crafter. These advances underscore AgentKits potential in making LLM agents effective and accessible for a wider range of applications. https://github.com/holmeswww/AgentKit"
