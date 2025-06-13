---
layout: publication
title: 'Appbench: Planning Of Multiple Apis From Various Apps For Complex User Instruction'
authors: Hongru Wang, Rui Wang, Boyang Xue, Heming Xia, Jingtao Cao, Zeming Liu, Jeff Z. Pan, Kam-fai Wong
conference: "Arxiv"
year: 2024
bibkey: wang2024planning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.19743'}
  - {name: "Code", url: 'https://github.com/ruleGreen/AppBench'}
tags: ['Has Code', 'GPT', 'Tools', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Large Language Models (LLMs) can interact with the real world by connecting
with versatile external APIs, resulting in better problem-solving and task
automation capabilities. Previous research primarily focuses on APIs with
limited arguments from a single source or overlooks the complex dependency
relationship between different APIs. However, it is essential to utilize
multiple APIs collaboratively from various sources (e.g., different Apps in the
iPhone), especially for complex user instructions. In this paper, we introduce
\texttt\{AppBench\}, the first benchmark to evaluate LLMs' ability to plan and
execute multiple APIs from various sources in order to complete the user's
task. Specifically, we consider two significant challenges in multiple APIs:
\textit\{1) graph structures:\} some APIs can be executed independently while
others need to be executed one by one, resulting in graph-like execution order;
and \textit\{2) permission constraints:\} which source is authorized to execute
the API call. We have experimental results on 9 distinct LLMs; e.g., GPT-4o
achieves only a 2.0% success rate at the most complex instruction, revealing
that the existing state-of-the-art LLMs still cannot perform well in this
situation even with the help of in-context learning and finetuning. Our code
and data are publicly available at https://github.com/ruleGreen/AppBench.
