---
layout: publication
title: Efficient Tool Use With Chain45;of45;abstraction Reasoning
authors: Gao Silin, Dwivedi-yu Jane, Yu Ping, Tan Xiaoqing Ellen, Pasunuru Ramakanth, Golovneva Olga, Sinha Koustuv, Celikyilmaz Asli, Bosselut Antoine, Wang Tianlu
conference: "Arxiv"
year: 2024
bibkey: gao2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17464"}
tags: ['Agentic', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Tools']
---
To achieve faithful reasoning that aligns with human expectations large language models (LLMs) need to ground their reasoning to real45;world knowledge (e.g. web facts math and physical rules). Tools help LLMs access this external knowledge but there remains challenges for fine45;tuning LLM agents (e.g. Toolformer) to invoke tools in multi45;step reasoning problems where inter45;connected tool calls require holistic and efficient tool usage planning. In this work we propose a new method for LLMs to better leverage tools in multi45;step reasoning. Our method Chain45;of45;Abstraction (CoA) trains LLMs to first decode reasoning chains with abstract placeholders and then call domain tools to reify each reasoning chain by filling in specific knowledge. This planning with abstract chains enables LLMs to learn more general reasoning strategies which are robust to shifts of domain knowledge (e.g. math results) relevant to different reasoning questions. It also allows LLMs to perform decoding and calling of external tools in parallel which avoids the inference delay caused by waiting for tool responses. In mathematical reasoning and Wiki QA domains we show that our method consistently outperforms previous chain45;of45;thought and tool45;augmented baselines on both in45;distribution and out45;of45;distribution test sets with an average ~637; absolute QA accuracy improvement. LLM agents trained with our method also show more efficient tool use with inference speed being on average ~1.4x faster than baseline tool45;augmented LLMs.
