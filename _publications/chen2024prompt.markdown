---
layout: publication
title: 'Prompt Optimization In Multi-step Tasks (PROMST): Integrating Human Feedback And Heuristic-based Sampling'
authors: Yongchao Chen, Jacob Arkin, Yilun Hao, Yang Zhang, Nicholas Roy, Chuchu Fan
conference: "EMNLP 2024 Main (The 2024 Conference on Empirical Methods on Natural Language Processing )"
year: 2024
bibkey: chen2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08702"}
  - {name: "Code", url: "https://github.com/yongchao98/PROMST"}
  - {name: "Code", url: "https://yongchao98.github.io/MIT-REALM-PROMST"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'RAG', 'Has Code', 'Prompting']
---
Prompt optimization aims to find the best prompt to a large language model
(LLM) for a given task. LLMs have been successfully used to help find and
improve prompt candidates for single-step tasks. However, realistic tasks for
agents are multi-step and introduce new challenges: (1) Prompt content is
likely to be more extensive and complex, making it more difficult for LLMs to
analyze errors, (2) the impact of an individual step is difficult to evaluate,
and (3) different people may have varied preferences about task execution.
While humans struggle to optimize prompts, they are good at providing feedback
about LLM outputs; we therefore introduce a new LLM-driven discrete prompt
optimization framework PRompt Optimization in Multi-Step Tasks (PROMST) that
incorporates human-designed feedback rules to automatically offer direct
suggestions for improvement. We also use an extra learned heuristic model that
predicts prompt performance to efficiently sample from prompt candidates. This
approach significantly outperforms both human-engineered prompts and several
other prompt optimization methods across 11 representative multi-step tasks (an
average 10.6%-29.3% improvement to current best methods on five LLMs
respectively). We believe our work can serve as a benchmark for automatic
prompt optimization for LLM-driven multi-step tasks. Datasets and Codes are
available at https://github.com/yongchao98/PROMST. Project Page is available at
https://yongchao98.github.io/MIT-REALM-PROMST.
