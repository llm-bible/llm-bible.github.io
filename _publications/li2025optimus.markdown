---
layout: publication
title: 'Optimus-2: Multimodal Minecraft Agent With Goal-observation-action Conditioned Policy'
authors: Zaijing Li, Yuquan Xie, Rui Shao, Gongwei Chen, Dongmei Jiang, Liqiang Nie
conference: "Arxiv"
year: 2025
bibkey: li2025optimus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19902"}
  - {name: "Code", url: "https://cybertronagent.github.io/Optimus-2.github.io/"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'BERT', 'Has Code']
---
Building an agent that can mimic human behavior patterns to accomplish
various open-world tasks is a long-term goal. To enable agents to effectively
learn behavioral patterns across diverse tasks, a key challenge lies in
modeling the intricate relationships among observations, actions, and language.
To this end, we propose Optimus-2, a novel Minecraft agent that incorporates a
Multimodal Large Language Model (MLLM) for high-level planning, alongside a
Goal-Observation-Action Conditioned Policy (GOAP) for low-level control. GOAP
contains (1) an Action-guided Behavior Encoder that models causal relationships
between observations and actions at each timestep, then dynamically interacts
with the historical observation-action sequence, consolidating it into
fixed-length behavior tokens, and (2) an MLLM that aligns behavior tokens with
open-ended language instructions to predict actions auto-regressively.
Moreover, we introduce a high-quality Minecraft Goal-Observation-Action (MGOA)\}
dataset, which contains 25,000 videos across 8 atomic tasks, providing about
30M goal-observation-action pairs. The automated construction method, along
with the MGOA dataset, can contribute to the community's efforts to train
Minecraft agents. Extensive experimental results demonstrate that Optimus-2
exhibits superior performance across atomic tasks, long-horizon tasks, and
open-ended instruction tasks in Minecraft. Please see the project page at
https://cybertronagent.github.io/Optimus-2.github.io/.
