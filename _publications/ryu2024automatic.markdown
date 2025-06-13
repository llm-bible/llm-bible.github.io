---
layout: publication
title: 'Curricullm: Automatic Task Curricula Design For Learning Complex Robot Skills Using Large Language Models'
authors: Kanghyun Ryu, Qiayuan Liao, Zhongyu Li, Payam Delgosha, Koushil Sreenath, Negar Mehr
conference: "Arxiv"
year: 2024
bibkey: ryu2024automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18382"}
  - {name: "Code", url: "https://iconlab.negarmehr.com/CurricuLLM/"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Curriculum learning is a training mechanism in reinforcement learning (RL)
that facilitates the achievement of complex policies by progressively
increasing the task difficulty during training. However, designing effective
curricula for a specific task often requires extensive domain knowledge and
human intervention, which limits its applicability across various domains. Our
core idea is that large language models (LLMs), with their extensive training
on diverse language data and ability to encapsulate world knowledge, present
significant potential for efficiently breaking down tasks and decomposing
skills across various robotics environments. Additionally, the demonstrated
success of LLMs in translating natural language into executable code for RL
agents strengthens their role in generating task curricula. In this work, we
propose CurricuLLM, which leverages the high-level planning and programming
capabilities of LLMs for curriculum design, thereby enhancing the efficient
learning of complex target tasks. CurricuLLM consists of: (Step 1) Generating
sequence of subtasks that aid target task learning in natural language form,
(Step 2) Translating natural language description of subtasks in executable
task code, including the reward code and goal distribution code, and (Step 3)
Evaluating trained policies based on trajectory rollout and subtask
description. We evaluate CurricuLLM in various robotics simulation
environments, ranging from manipulation, navigation, and locomotion, to show
that CurricuLLM can aid learning complex robot control tasks. In addition, we
validate humanoid locomotion policy learned through CurricuLLM in real-world.
Project website is https://iconlab.negarmehr.com/CurricuLLM/
