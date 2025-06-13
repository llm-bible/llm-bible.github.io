---
layout: publication
title: 'Dynasaur: Large Language Agents Beyond Predefined Actions'
authors: Dang Nguyen, Viet Dac Lai, Seunghyun Yoon, Ryan A. Rossi, Handong Zhao, Ruiyi Zhang, Puneet Mathur, Nedim Lipka, Yu Wang, Trung Bui, Franck Dernoncourt, Tianyi Zhou
conference: "Arxiv"
year: 2024
bibkey: nguyen2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01747"}
  - {name: "Code", url: "https://github.com/adobe-research/dynasaur"}
tags: ['Tools', 'Agentic', 'Has Code', 'Reinforcement Learning']
---
Existing LLM agent systems typically select actions from a fixed and predefined set at every step. While this approach is effective in closed, narrowly scoped environments, it presents two major challenges for real-world, open-ended scenarios: (1) it significantly restricts the planning and acting capabilities of LLM agents, and (2) it requires substantial human effort to enumerate and implement all possible actions, which is impractical in complex environments with a vast number of potential actions. To address these limitations, we propose an LLM agent framework that can dynamically create and compose actions as needed. In this framework, the agent interacts with its environment by generating and executing programs written in a general-purpose programming language. Moreover, generated actions are accumulated over time for future reuse. Our extensive experiments across multiple benchmarks show that this framework significantly improves flexibility and outperforms prior methods that rely on a fixed action set. Notably, it enables LLM agents to adapt and recover in scenarios where predefined actions are insufficient or fail due to unforeseen edge cases. Our code can be found in https://github.com/adobe-research/dynasaur.
