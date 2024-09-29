---
layout: publication
title: "Hierarchical In-context Reinforcement Learning With Hindsight Modular Reflections For Planning"
authors: Sun Chuanneng, Huang Songjun, Pompili Dario
conference: "Arxiv"
year: 2024
bibkey: sun2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06520"}
tags: ['Agentic', 'Efficiency And Optimization', 'In Context Learning', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable abilities in various language tasks making them promising candidates for decision-making in robotics. Inspired by Hierarchical Reinforcement Learning (HRL) we propose Hierarchical in-Context Reinforcement Learning (HCRL) a novel framework that decomposes complex tasks into sub-tasks using an LLM-based high-level policy in which a complex task is decomposed into sub-tasks by a high-level policy on-the-fly. The sub-tasks defined by goals are assigned to the low-level policy to complete. Once the LLM agent determines that the goal is finished a new goal will be proposed. To improve the agents performance in multi-episode execution we propose Hindsight Modular Reflection (HMR) where instead of reflecting on the full trajectory we replace the task objective with intermediate goals and let the agent reflect on shorter trajectories to improve reflection efficiency. We evaluate the decision-making ability of the proposed HCRL in three benchmark environments--ALFWorld Webshop and HotpotQA. Results show that HCRL can achieve 937; 4237; and 1037; performance improvement in 5 episodes of execution over strong in-context learning baselines.
