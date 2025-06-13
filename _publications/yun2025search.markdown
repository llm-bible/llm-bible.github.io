---
layout: publication
title: 'Eicopilot: Search And Explore Enterprise Information Over Large-scale Knowledge Graphs With Llm-driven Agents'
authors: Yuhui Yun, Huilong Ye, Xinru Li, Ruojia Li, Jingfeng Deng, Li Li, Haoyi Xiong
conference: "Arxiv"
year: 2025
bibkey: yun2025search
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.13746'}
tags: ['Applications', 'Fine-Tuning', 'Agentic', 'Tools']
---
The paper introduces EICopilot, an novel agent-based solution enhancing
search and exploration of enterprise registration data within extensive online
knowledge graphs like those detailing legal entities, registered capital, and
major shareholders. Traditional methods necessitate text-based queries and
manual subgraph explorations, often resulting in time-consuming processes.
EICopilot, deployed as a chatbot via Baidu Enterprise Search, improves this
landscape by utilizing Large Language Models (LLMs) to interpret natural
language queries. This solution automatically generates and executes Gremlin
scripts, providing efficient summaries of complex enterprise relationships.
Distinct feature a data pre-processing pipeline that compiles and annotates
representative queries into a vector database of examples for In-context
learning (ICL), a comprehensive reasoning pipeline combining Chain-of-Thought
with ICL to enhance Gremlin script generation for knowledge graph search and
exploration, and a novel query masking strategy that improves intent
recognition for heightened script accuracy. Empirical evaluations demonstrate
the superior performance of EICopilot, including speed and accuracy, over
baseline methods, with the *Full Mask* variant achieving a syntax error
rate reduction to as low as 10.00% and an execution correctness of up to
82.14%. These components collectively contribute to superior querying
capabilities and summarization of intricate datasets, positioning EICopilot as
a groundbreaking tool in the exploration and exploitation of large-scale
knowledge graphs for enterprise information search.
