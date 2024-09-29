---
layout: publication
title: "Memocrs: Memory-enhanced Sequential Conversational Recommender Systems With Large Language Models"
authors: Xi Yunjia, Liu Weiwen, Lin Jianghao, Chen Bo, Tang Ruiming, Zhang Weinan, Yu Yong
conference: "Arxiv"
year: 2024
bibkey: xi2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04960"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Conversational recommender systems (CRSs) aim to capture user preferences and provide personalized recommendations through multi-round natural language dialogues. However most existing CRS models mainly focus on dialogue comprehension and preferences mining from the current dialogue session overlooking user preferences in historical dialogue sessions. The preferences embedded in the users historical dialogue sessions and the current session exhibit continuity and sequentiality and we refer to CRSs with this characteristic as sequential CRSs. In this work we leverage memory-enhanced LLMs to model the preference continuity primarily focusing on addressing two key issues (1) redundancy and noise in historical dialogue sessions and (2) the cold-start users problem. To this end we propose a Memory-enhanced Conversational Recommender System Framework with Large Language Models (dubbed MemoCRS) consisting of user-specific memory and general memory. User-specific memory is tailored to each user for their personalized interests and implemented by an entity-based memory bank to refine preferences and retrieve relevant memory thereby reducing the redundancy and noise of historical sessions. The general memory encapsulating collaborative knowledge and reasoning guidelines can provide shared knowledge for users especially cold-start users. With the two kinds of memory LLMs are empowered to deliver more precise and tailored recommendations for each user. Extensive experiments on both Chinese and English datasets demonstrate the effectiveness of MemoCRS.
