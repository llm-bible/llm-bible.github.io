---
layout: publication
title: Describe Explain Plan And Select Interactive Planning With Large Language Models Enables Open45;world Multi45;task Agents
authors: Zihao Wang, Shaofei Cai, Guanzhou Chen, Anji Liu, Xiaojian Ma, Yitao Liang
conference: "Arxiv"
year: 2023
bibkey: wang2023plan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2302.01560v3"}
  - {name: "Code", url: "https://github.com/CraftJarvis/MC&#45;Planner"}
tags: ['Agentic', 'Fine Tuning', 'Has Code', 'Interpretability And Explainability', 'Pretraining Methods', 'Reinforcement Learning']
---
We investigate the challenge of task planning for multi45;task embodied agents in open45;world environments. Two main difficulties are identified 1) executing plans in an open45;world environment (e.g. Minecraft) necessitates accurate and multi45;step reasoning due to the long45;term nature of tasks and 2) as vanilla planners do not consider how easy the current agent can achieve a given sub45;task when ordering parallel sub45;goals within a complicated plan the resulting plan could be inefficient or even infeasible. To this end we propose underline123;D125;escribe underline123;E125;xplain underline123;P125;lan and underline123;S125;elect (textbf123;DEPS125;) an interactive planning approach based on Large Language Models (LLMs). DEPS facilitates better error correction on initial LLM45;generated textit123;plan125; by integrating textit123;description125; of the plan execution process and providing self45;textit123;explanation125; of feedback when encountering failures during the extended planning phases. Furthermore it includes a goal textit123;selector125; which is a trainable module that ranks parallel candidate sub45;goals based on the estimated steps of completion consequently refining the initial plan. Our experiments mark the milestone of the first zero45;shot multi45;task agent that can robustly accomplish 70+ Minecraft tasks and nearly double the overall performances. Further testing reveals our methods general effectiveness in popularly adopted non45;open45;ended domains as well (i.e. ALFWorld and tabletop manipulation). The ablation and exploratory studies detail how our design beats the counterparts and provide a promising update on the texttt123;ObtainDiamond125; grand challenge with our approach. The code is released at https://github.com/CraftJarvis/MC&#45;Planner.
