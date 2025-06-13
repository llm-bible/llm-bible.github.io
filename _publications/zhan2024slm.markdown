---
layout: publication
title: 'Slm-mod: Small Language Models Surpass Llms At Content Moderation'
authors: Xianyang Zhan, Agam Goyal, Yilun Chen, Eshwar Chandrasekharan, Koustuv Saha
conference: "Arxiv"
year: 2024
bibkey: zhan2024slm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13155"}
  - {name: "Code", url: "https://github.com/AGoyal0512/SLM-Mod"}
tags: ['Tools', 'RAG', 'Has Code', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have shown promise in many natural language
understanding tasks, including content moderation. However, these models can be
expensive to query in real-time and do not allow for a community-specific
approach to content moderation. To address these challenges, we explore the use
of open-source small language models (SLMs) for community-specific content
moderation tasks. We fine-tune and evaluate SLMs (less than 15B parameters) by
comparing their performance against much larger open- and closed-sourced models
in both a zero-shot and few-shot setting. Using 150K comments from 15 popular
Reddit communities, we find that SLMs outperform zero-shot LLMs at content
moderation -- 11.5% higher accuracy and 25.7% higher recall on average across
all communities. Moreover, few-shot in-context learning leads to only a
marginal increase in the performance of LLMs, still lacking compared to SLMs.
We further show the promise of cross-community content moderation, which has
implications for new communities and the development of cross-platform
moderation techniques. Finally, we outline directions for future work on
language model based content moderation. Code and models can be found at
https://github.com/AGoyal0512/SLM-Mod.
