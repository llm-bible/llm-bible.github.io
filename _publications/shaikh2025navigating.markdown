---
layout: publication
title: 'Navigating Rifts In Human-llm Grounding: Study And Benchmark'
authors: Omar Shaikh, Hussein Mozannar, Gagan Bansal, Adam Fourney, Eric Horvitz
conference: "Arxiv"
year: 2025
bibkey: shaikh2025navigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13975'}
tags: ['Reinforcement Learning', 'Prompting']
---
Language models excel at following instructions but often struggle with the collaborative aspects of conversation that humans naturally employ. This limitation in grounding -- the process by which conversation participants establish mutual understanding -- can lead to outcomes ranging from frustrated users to serious consequences in high-stakes scenarios. To systematically study grounding challenges in human-LLM interactions, we analyze logs from three human-assistant datasets: WildChat, MultiWOZ, and Bing Chat. We develop a taxonomy of grounding acts and build models to annotate and forecast grounding behavior. Our findings reveal significant differences in human-human and human-LLM grounding: LLMs were three times less likely to initiate clarification and sixteen times less likely to provide follow-up requests than humans. Additionally, we find that early grounding failures predict later interaction breakdowns. Building on these insights, we introduce Rifts, a benchmark derived from publicly available LLM interaction data containing situations where LLMs fail to initiate grounding. We note that current frontier models perform poorly on Rifts, highlighting the need to reconsider how we train and prompt LLMs for human interaction. To this end, we develop a preliminary intervention aimed at mitigating grounding failures.
