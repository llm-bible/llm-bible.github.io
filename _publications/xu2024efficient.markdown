---
layout: publication
title: "Conveyor: Efficient Tool-aware LLM Serving With Tool Partial Execution"
authors: Xu Yechen, Kong Xinhao, Chen Tingjun, Zhuo Danyang
conference: "Arxiv"
year: 2024
bibkey: xu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00059"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
The complexity of large language model (LLM) serving workloads has substantially increased due to the integration with external tool invocations such as ChatGPT plugins. In this paper we identify a new opportunity for efficient LLM serving for requests that trigger tools tool partial execution alongside LLM decoding. To this end we design Conveyor an efficient LLM serving system optimized for handling requests involving external tools. We introduce a novel interface for tool developers to expose partial execution opportunities to the LLM serving system and a request scheduler that facilitates partial tool execution. Our results demonstrate that tool partial execution can improve request completion latency by up to 38.837;.
