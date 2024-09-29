---
layout: publication
title: Formal45;llm Integrating Formal Language And Natural Language For Controllable Llm45;based Agents
authors: Li Zelong, Hua Wenyue, Wang Hao, Zhu He, Zhang Yongfeng
conference: "Arxiv"
year: 2024
bibkey: li2024formal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00798"}
  - {name: "Code", url: "https://github.com/agiresearch/Formal&#45;LLM"}
tags: ['Agentic', 'Applications', 'Has Code', 'Tools']
---
Recent advancements on Large Language Models (LLMs) enable AI Agents to automatically generate and execute multi45;step plans to solve complex tasks. However since LLMs content generation process is hardly controllable current LLM45;based agents frequently generate invalid or non45;executable plans which jeopardizes the performance of the generated plans and corrupts users trust in LLM45;based agents. In response this paper proposes a novel Formal45;LLM framework for LLM45;based agents by integrating the expressiveness of natural language and the precision of formal language. Specifically the framework allows agent developers to express their requirements or constraints for the planning process as an automaton. A stack45;based LLM plan generation process is then conducted under the supervision of the automaton to ensure that the generated plan satisfies the constraints making the planning process controllable. We conduct experiments on both benchmark tasks and practical real45;life tasks and our framework achieves over 5037; overall performance increase which validates the feasibility and effectiveness of employing Formal45;LLM to guide the plan generation of agents preventing the agents from generating invalid and unsuccessful plans. Further more controllable LLM45;based agents can facilitate the broader utilization of LLM in application scenarios where high validity of planning is essential. The source code of this work is available at https://github.com/agiresearch/Formal&#45;LLM.
