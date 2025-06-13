---
layout: publication
title: 'Graphotter: Evolving Llm-based Graph Reasoning For Complex Table Question Answering'
authors: Qianlong Li, Chen Huang, Shuai Li, Yuanxin Xiang, Deng Xiong, Wenqiang Lei
conference: "Arxiv"
year: 2024
bibkey: li2024evolving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.01230'}
  - {name: "Code", url: 'https://github.com/JDing0521/GraphOTTER'}
tags: ['Has Code', 'RAG', 'Applications', 'Prompting', 'Reinforcement Learning']
---
Complex Table Question Answering involves providing accurate answers to
specific questions based on intricate tables that exhibit complex layouts and
flexible header locations. Despite considerable progress having been made in
the LLM era, the reasoning processes of existing methods are often implicit,
feeding the entire table into prompts, making it difficult to effectively
filter out irrelevant information in the table. To this end, we propose
GraphOTTER that explicitly establishes the reasoning process to pinpoint the
correct answers. In particular, GraphOTTER leverages a graph-based
representation, transforming the complex table into an undirected graph. It
then conducts step-by-step reasoning on the graph, with each step guided by a
set of pre-defined intermediate reasoning actions. As such, it constructs a
clear reasoning path and effectively identifies the answer to a given question.
Comprehensive experiments on two benchmark datasets and two LLM backbones
demonstrate the effectiveness of GraphOTTER. Further analysis indicates that
its success may be attributed to the ability to efficiently filter out
irrelevant information, thereby focusing the reasoning process on the most
pertinent data. Our code and experimental datasets are available at
\url\{https://github.com/JDing0521/GraphOTTER\}.
