---
layout: publication
title: Modeling Complex Mathematical Reasoning via Large Language Model based MathAgent
authors: Liao Haoran, Du Qinyi, Hu Shaohua, He Hao, Xu Yanyan, Tian Jidong, Jin Yaohui
conference: "Arxiv"
year: 2023
bibkey: liao2023modeling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.08926"}
tags: ['Agentic', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Large language models (LLMs) face challenges in solving complex mathematical problems that require comprehensive capacities to parse the statements associate domain knowledge perform compound logical reasoning and integrate the intermediate rationales. Tackling all these problems once could be arduous for LLMs thus leading to confusion in generation. In this work we explore the potential of enhancing LLMs with agents by meticulous decomposition and modeling of mathematical reasoning process. Specifically we propose a formal description of the mathematical solving and extend LLMs with an agent-based zero-shot framework named bfPlanner-bfReasoner-bfExecutor-bfReflector (PRER). We further provide and implement two MathAgents that define the logical forms and inherent relations via a pool of actions in different grains and orientations MathAgent-M adapts its actions to LLMs while MathAgent-H aligns with humankind. Experiments on miniF2F and MATH have demonstrated the effectiveness of PRER and proposed MathAgents achieving an increase of 12.3(53.9xrightarrow66.2) on the MiniF2F 9.2 (49.8xrightarrow59.0) on MATH and 13.2(23.2xrightarrow35.4) for level-5 problems of MATH against GPT-4. Further analytical results provide more insightful perspectives on exploiting the behaviors of LLMs as agents.
