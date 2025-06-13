---
layout: publication
title: 'MAC-SQL: A Multi-agent Collaborative Framework For Text-to-sql'
authors: Bing Wang, Changyu Ren, Jian Yang, Xinnian Liang, Jiaqi Bai, Linzheng Chai, Zhao Yan, Qian-wen Zhang, Di Yin, Xing Sun, Zhoujun Li
conference: "Arxiv"
year: 2023
bibkey: wang2023mac
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.11242'}
  - {name: "Code", url: 'https://github.com/wbbeyourself/MAC-SQL)'}
tags: ['Agentic', 'Has Code', 'Few-Shot', 'RAG', 'Model Architecture', 'Tools', 'GPT']
---
Recent LLM-based Text-to-SQL methods usually suffer from significant
performance degradation on "huge" databases and complex user questions that
require multi-step reasoning. Moreover, most existing methods neglect the
crucial significance of LLMs utilizing external tools and model collaboration.
To address these challenges, we introduce MAC-SQL, a novel LLM-based
multi-agent collaborative framework. Our framework comprises a core decomposer
agent for Text-to-SQL generation with few-shot chain-of-thought reasoning,
accompanied by two auxiliary agents that utilize external tools or models to
acquire smaller sub-databases and refine erroneous SQL queries. The decomposer
agent collaborates with auxiliary agents, which are activated as needed and can
be expanded to accommodate new features or tools for effective Text-to-SQL
parsing. In our framework, We initially leverage GPT-4 as the strong backbone
LLM for all agent tasks to determine the upper bound of our framework. We then
fine-tune an open-sourced instruction-followed model, SQL-Llama, by leveraging
Code Llama 7B, to accomplish all tasks as GPT-4 does. Experiments show that
SQL-Llama achieves a comparable execution accuracy of 43.94, compared to the
baseline accuracy of 46.35 for vanilla GPT-4. At the time of writing,
MAC-SQL+GPT-4 achieves an execution accuracy of 59.59 when evaluated on the
BIRD benchmark, establishing a new state-of-the-art (SOTA) on its holdout test
set (https://github.com/wbbeyourself/MAC-SQL).
