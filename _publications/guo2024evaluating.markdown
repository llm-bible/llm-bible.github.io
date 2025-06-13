---
layout: publication
title: 'Evaluating And Enhancing Llms For Multi-turn Text-to-sql With Multiple Question Types'
authors: Ziming Guo, Chao Ma, Yinggang Sun, Tiancheng Zhao, Guangyao Wang, Hai Huang
conference: "Arxiv"
year: 2024
bibkey: guo2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17867"}
  - {name: "Code", url: "https://mcxiaoxiao.github.io/MMSQL"}
tags: ['Agentic', 'Has Code', 'Tools', 'Reinforcement Learning']
---
Recent advancements in large language models (LLMs) have significantly
advanced text-to-SQL systems. However, most LLM-based methods often narrowly
focus on SQL generation, neglecting the complexities of real-world
conversational queries. This oversight can lead to unreliable responses,
particularly for ambiguous questions that cannot be directly addressed with
SQL. To bridge this gap, we propose MMSQL, a comprehensive test suite designed
to evaluate the question classification and SQL generation capabilities of LLMs
by simulating real-world scenarios with diverse question types and multi-turn
Q&A interactions. Using MMSQL, we assessed the performance of popular LLMs,
including both open-source and closed-source models, and identified key factors
impacting their performance in such scenarios. Moreover, we introduce an
LLM-based multi-agent framework that employs specialized agents to identify
question types and determine appropriate answering strategies. Our experiments
demonstrate that this approach significantly enhances the model's ability to
navigate the complexities of conversational dynamics, effectively handling the
diverse and complex nature of user queries. Our dataset and code are publicly
available at https://mcxiaoxiao.github.io/MMSQL.
