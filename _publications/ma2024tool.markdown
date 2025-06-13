---
layout: publication
title: 'Sciagent: Tool-augmented Language Models For Scientific Reasoning'
authors: Yubo Ma, Zhibin Gou, Junheng Hao, Ruochen Xu, Shuohang Wang, Liangming Pan, Yujiu Yang, Yixin Cao, Aixin Sun, Hany Awadalla, Weizhu Chen
conference: "Arxiv"
year: 2024
bibkey: ma2024tool
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11451"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT']
---
Scientific reasoning poses an excessive challenge for even the most advanced
Large Language Models (LLMs). To make this task more practical and solvable for
LLMs, we introduce a new task setting named tool-augmented scientific
reasoning. This setting supplements LLMs with scalable toolsets, and shifts the
focus from pursuing an omniscient problem solver to a proficient tool-user. To
facilitate the research of such setting, we construct a tool-augmented training
corpus named MathFunc which encompasses over 30,000 samples and roughly 6,000
tools. Building on MathFunc, we develop SciAgent to retrieve, understand and,
if necessary, use tools for scientific problem solving. Additionally, we craft
a benchmark, SciToolBench, spanning five scientific domains to evaluate LLMs'
abilities with tool assistance. Extensive experiments on SciToolBench confirm
the effectiveness of SciAgent. Notably, SciAgent-Mistral-7B surpasses other
LLMs with the same size by more than 13% in absolute accuracy. Furthermore,
SciAgent-DeepMath-7B shows much superior performance than ChatGPT.
