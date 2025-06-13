---
layout: publication
title: 'Interpersonal Memory Matters: A New Task For Proactive Dialogue Utilizing Conversational History'
authors: Bowen Wu, Wenqing Wang, Haoran Li, Ying Li, Jingsong Yu, Baoxun Wang
conference: "Arxiv"
year: 2025
bibkey: wu2025interpersonal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05150'}
  - {name: "Code", url: 'https://github.com/FrontierLabs/MapDia'}
tags: ['Agentic', 'Has Code', 'RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Proactive dialogue systems aim to empower chatbots with the capability of
leading conversations towards specific targets, thereby enhancing user
engagement and service autonomy. Existing systems typically target pre-defined
keywords or entities, neglecting user attributes and preferences implicit in
dialogue history, hindering the development of long-term user intimacy. To
address these challenges, we take a radical step towards building a more
human-like conversational agent by integrating proactive dialogue systems with
long-term memory into a unified framework. Specifically, we define a novel task
named Memory-aware Proactive Dialogue (MapDia). By decomposing the task, we
then propose an automatic data construction method and create the first Chinese
Memory-aware Proactive Dataset (ChMapData). Furthermore, we introduce a joint
framework based on Retrieval Augmented Generation (RAG), featuring three
modules: Topic Summarization, Topic Retrieval, and Proactive Topic-shifting
Detection and Generation, designed to steer dialogues towards relevant
historical topics at the right time. The effectiveness of our dataset and
models is validated through both automatic and human evaluations. We release
the open-source framework and dataset at
https://github.com/FrontierLabs/MapDia.
