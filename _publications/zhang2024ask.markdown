---
layout: publication
title: Ask-before-plan&#58; Proactive Language Agents For Real-world Planning
authors: Zhang Xuan, Deng Yang, Ren Zifeng, Ng See-kiong, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: zhang2024ask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12639"}
tags: ['Agentic', 'Fine Tuning', 'Reinforcement Learning', 'Tools']
---
The evolution of large language models (LLMs) has enhanced the planning capabilities of language agents in diverse real-world scenarios. Despite these advancements the potential of LLM-powered agents to comprehend ambiguous user instructions for reasoning and decision-making is still under exploration. In this work we introduce a new task Proactive Agent Planning which requires language agents to predict clarification needs based on user-agent conversation and agent-environment interaction invoke external tools to collect valid information and generate a plan to fulfill the users demands. To study this practical problem we establish a new benchmark dataset Ask-before-Plan. To tackle the deficiency of LLMs in proactive planning we propose a novel multi-agent framework Clarification-Execution-Planning ((textttCEP)) which consists of three agents specialized in clarification execution and planning. We introduce the trajectory tuning scheme for the clarification agent and static execution agent as well as the memory recollection mechanism for the dynamic execution agent. Extensive evaluations and comprehensive analyses conducted on the Ask-before-Plan dataset validate the effectiveness of our proposed framework.
