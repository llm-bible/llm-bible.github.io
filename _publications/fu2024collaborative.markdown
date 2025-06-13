---
layout: publication
title: 'CAMPHOR: Collaborative Agents For Multi-input Planning And High-order Reasoning On Device'
authors: Yicheng Fu, Raviteja Anantha, Jianpeng Cheng
conference: "Arxiv"
year: 2024
bibkey: fu2024collaborative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09407'}
tags: ['Agentic', 'RAG', 'Model Architecture', 'Tools', 'Prompting', 'Reinforcement Learning']
---
While server-side Large Language Models (LLMs) demonstrate proficiency in
function calling and complex reasoning, deploying Small Language Models (SLMs)
directly on devices brings opportunities to improve latency and privacy but
also introduces unique challenges for accuracy and memory. We introduce
CAMPHOR, an innovative on-device SLM multi-agent framework designed to handle
multiple user inputs and reason over personal context locally, ensuring privacy
is maintained. CAMPHOR employs a hierarchical architecture where a high-order
reasoning agent decomposes complex tasks and coordinates expert agents
responsible for personal context retrieval, tool interaction, and dynamic plan
generation. By implementing parameter sharing across agents and leveraging
prompt compression, we significantly reduce model size, latency, and memory
usage. To validate our approach, we present a novel dataset capturing
multi-agent task trajectories centered on personalized mobile assistant
use-cases. Our experiments reveal that fine-tuned SLM agents not only surpass
closed-source LLMs in task completion F1 by~35% but also eliminate the need
for server-device communication, all while enhancing privacy.
