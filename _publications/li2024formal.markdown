---
layout: publication
title: 'Formal-llm: Integrating Formal Language And Natural Language For Controllable Llm-based Agents'
authors: Zelong Li, Wenyue Hua, Hao Wang, He Zhu, Yongfeng Zhang
conference: "Arxiv"
year: 2024
bibkey: li2024formal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.00798'}
  - {name: "Code", url: 'https://github.com/agiresearch/Formal-LLM'}
tags: ['Agentic', 'Has Code', 'Tools']
---
Recent advancements on Large Language Models (LLMs) enable AI Agents to
automatically generate and execute multi-step plans to solve complex tasks.
However, since LLM's content generation process is hardly controllable, current
LLM-based agents frequently generate invalid or non-executable plans, which
jeopardizes the performance of the generated plans and corrupts users' trust in
LLM-based agents. In response, this paper proposes a novel "Formal-LLM"
framework for LLM-based agents by integrating the expressiveness of natural
language and the precision of formal language. Specifically, the framework
allows agent developers to express their requirements or constraints for the
planning process as an automaton. A stack-based LLM plan generation process is
then conducted under the supervision of the automaton to ensure that the
generated plan satisfies the constraints, making the planning process
controllable. We conduct experiments on both benchmark tasks and practical
real-life tasks, and our framework achieves over 50% overall performance
increase, which validates the feasibility and effectiveness of employing
Formal-LLM to guide the plan generation of agents, preventing the agents from
generating invalid and unsuccessful plans. Further, more controllable LLM-based
agents can facilitate the broader utilization of LLM in application scenarios
where high validity of planning is essential. The source code of this work is
available at https://github.com/agiresearch/Formal-LLM.
