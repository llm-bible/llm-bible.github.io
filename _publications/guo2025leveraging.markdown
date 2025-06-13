---
layout: publication
title: 'Leveraging Pre-trained Large Language Models With Refined Prompting For Online Task And Motion Planning'
authors: Huihui Guo, Huilong Pi, Yunchuan Qin, Zhuo Tang, Kenli Li
conference: "Arxiv"
year: 2025
bibkey: guo2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.21596"}
tags: ['Security', 'Tools', 'RAG', 'Fine-Tuning', 'Prompting']
---
With the rapid advancement of artificial intelligence, there is an increasing
demand for intelligent robots capable of assisting humans in daily tasks and
performing complex operations. Such robots not only require task planning
capabilities but must also execute tasks with stability and robustness. In this
paper, we present a closed-loop task planning and acting system, LLM-PAS, which
is assisted by a pre-trained Large Language Model (LLM). While LLM-PAS plans
long-horizon tasks in a manner similar to traditional task and motion planners,
it also emphasizes the execution phase of the task. By transferring part of the
constraint-checking process from the planning phase to the execution phase,
LLM-PAS enables exploration of the constraint space and delivers more accurate
feedback on environmental anomalies during execution. The reasoning
capabilities of the LLM allow it to handle anomalies that cannot be addressed
by the robust executor. To further enhance the system's ability to assist the
planner during replanning, we propose the First Look Prompting (FLP) method,
which induces LLM to generate effective PDDL goals. Through comparative
prompting experiments and systematic experiments, we demonstrate the
effectiveness and robustness of LLM-PAS in handling anomalous conditions during
task execution.
