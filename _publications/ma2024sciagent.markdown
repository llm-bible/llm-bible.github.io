---
layout: publication
title: SciAgent Tool-augmented Language Models for Scientific Reasoning
authors: Ma Yubo, Gou Zhibin, Hao Junheng, Xu Ruochen, Wang Shuohang, Pan Liangming, Yang Yujiu, Cao Yixin, Sun Aixin, Awadalla Hany, Chen Weizhu
conference: "Arxiv"
year: 2024
bibkey: ma2024sciagent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11451"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Scientific reasoning poses an excessive challenge for even the most advanced Large Language Models (LLMs). To make this task more practical and solvable for LLMs we introduce a new task setting named tool-augmented scientific reasoning. This setting supplements LLMs with scalable toolsets and shifts the focus from pursuing an omniscient problem solver to a proficient tool-user. To facilitate the research of such setting we construct a tool-augmented training corpus named MathFunc which encompasses over 30000 samples and roughly 6000 tools. Building on MathFunc we develop SciAgent to retrieve understand and if necessary use tools for scientific problem solving. Additionally we craft a benchmark SciToolBench spanning five scientific domains to evaluate LLMs abilities with tool assistance. Extensive experiments on SciToolBench confirm the effectiveness of SciAgent. Notably SciAgent-Mistral-7B surpasses other LLMs with the same size by more than 13 in absolute accuracy. Furthermore SciAgent-DeepMath-7B shows much superior performance than ChatGPT.
