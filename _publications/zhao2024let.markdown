---
layout: publication
title: 'Let Me Do It For You: Towards LLM Empowered Recommendation Via Tool Learning'
authors: Zhao Yuyue, Wu Jiancan, Wang Xiang, Tang Wei, Wang Dingxian, De Rijke Maarten
conference: "Arxiv"
year: 2024
bibkey: zhao2024let
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15114"}
tags: ['RAG', 'Reinforcement Learning', 'Tools']
---
'Conventional recommender systems (RSs) face challenges in precisely capturing users'' fine-grained preferences. Large language models (LLMs) have shown capabilities in commonsense reasoning and leveraging external tools that may help address these challenges. However, existing LLM-based RSs suffer from hallucinations, misalignment between the semantic space of items and the behavior space of users, or overly simplistic control strategies (e.g., whether to rank or directly present existing results). To bridge these gap, we introduce ToolRec, a framework for LLM-empowered recommendations via tool learning that uses LLMs as surrogate users, thereby guiding the recommendation process and invoking external tools to generate a recommendation list that aligns closely with users'' nuanced preferences. We formulate the recommendation process as a process aimed at exploring user interests in attribute granularity. The process factors in the nuances of the context and user preferences. The LLM then invokes external tools based on a user''s attribute instructions and probes different segments of the item pool. We consider two types of attribute-oriented tools: rank tools and retrieval tools. Through the integration of LLMs, ToolRec enables conventional recommender systems to become external tools with a natural language interface. Extensive experiments verify the effectiveness of ToolRec, particularly in scenarios that are rich in semantic content.'
