---
layout: publication
title: Hierarchical In45;context Reinforcement Learning With Hindsight Modular Reflections For Planning
authors: Sun Chuanneng, Huang Songjun, Pompili Dario
conference: "Arxiv"
year: 2024
bibkey: sun2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06520"}
tags: ['Agentic', 'Efficiency And Optimization', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable abilities in various language tasks making them promising candidates for decision45;making in robotics. Inspired by Hierarchical Reinforcement Learning (HRL) we propose Hierarchical in45;Context Reinforcement Learning (HCRL) a novel framework that decomposes complex tasks into sub45;tasks using an LLM45;based high45;level policy in which a complex task is decomposed into sub45;tasks by a high45;level policy on45;the45;fly. The sub45;tasks defined by goals are assigned to the low45;level policy to complete. Once the LLM agent determines that the goal is finished a new goal will be proposed. To improve the agents performance in multi45;episode execution we propose Hindsight Modular Reflection (HMR) where instead of reflecting on the full trajectory we replace the task objective with intermediate goals and let the agent reflect on shorter trajectories to improve reflection efficiency. We evaluate the decision45;making ability of the proposed HCRL in three benchmark environments45;45;ALFWorld Webshop and HotpotQA. Results show that HCRL can achieve 937; 4237; and 1037; performance improvement in 5 episodes of execution over strong in45;context learning baselines.
