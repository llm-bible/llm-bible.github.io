---
layout: publication
title: 'MAS-GPT: Training Llms To Build Llm-based Multi-agent Systems'
authors: Rui Ye, Shuo Tang, Rui Ge, Yaxin Du, Zhenfei Yin, Siheng Chen, Jing Shao
conference: "Arxiv"
year: 2025
bibkey: ye2025mas
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03686'}
  - {name: "Code", url: 'https://github.com/rui-ye/MAS-GPT'}
tags: ['Agentic', 'Has Code', 'Agent', 'Efficiency and Optimization', 'Training Techniques', 'GPT', 'Model Architecture']
---
LLM-based multi-agent systems (MAS) have shown significant potential in
tackling diverse tasks. However, to design effective MAS, existing approaches
heavily rely on manual configurations or multiple calls of advanced LLMs,
resulting in inadaptability and high inference costs. In this paper, we
simplify the process of building an MAS by reframing it as a generative
language task, where the input is a user query and the output is a
corresponding MAS. To address this novel task, we unify the representation of
MAS as executable code and propose a consistency-oriented data construction
pipeline to create a high-quality dataset comprising coherent and consistent
query-MAS pairs. Using this dataset, we train MAS-GPT, an open-source
medium-sized LLM that is capable of generating query-adaptive MAS within a
single LLM inference. The generated MAS can be seamlessly applied to process
user queries and deliver high-quality responses. Extensive experiments on 9
benchmarks and 5 LLMs show that the proposed MAS-GPT consistently outperforms
10+ baseline MAS methods on diverse settings, indicating MAS-GPT's high
effectiveness, efficiency and strong generalization ability. Code will be
available at https://github.com/rui-ye/MAS-GPT.
