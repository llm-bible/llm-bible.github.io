---
layout: publication
title: 'A Multi-agent Conversational Recommender System'
authors: Jiabao Fang, Shen Gao, Pengjie Ren, Xiuying Chen, Suzan Verberne, Zhaochun Ren
conference: "Arxiv"
year: 2024
bibkey: fang2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01135"}
tags: ['RAG', 'Agentic', 'Prompting', 'Tools']
---
Due to strong capabilities in conducting fluent, multi-turn conversations
with users, Large Language Models (LLMs) have the potential to further improve
the performance of Conversational Recommender System (CRS). Unlike the aimless
chit-chat that LLM excels at, CRS has a clear target. So it is imperative to
control the dialogue flow in the LLM to successfully recommend appropriate
items to the users. Furthermore, user feedback in CRS can assist the system in
better modeling user preferences, which has been ignored by existing studies.
However, simply prompting LLM to conduct conversational recommendation cannot
address the above two key challenges.
  In this paper, we propose Multi-Agent Conversational Recommender System
(MACRS) which contains two essential modules. First, we design a multi-agent
act planning framework, which can control the dialogue flow based on four
LLM-based agents. This cooperative multi-agent framework will generate various
candidate responses based on different dialogue acts and then choose the most
appropriate response as the system response, which can help MACRS plan suitable
dialogue acts. Second, we propose a user feedback-aware reflection mechanism
which leverages user feedback to reason errors made in previous turns to adjust
the dialogue act planning, and higher-level user information from implicit
semantics. We conduct extensive experiments based on user simulator to
demonstrate the effectiveness of MACRS in recommendation and user preferences
collection. Experimental results illustrate that MACRS demonstrates an
improvement in user interaction experience compared to directly using LLMs.
