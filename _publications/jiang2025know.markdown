---
layout: publication
title: 'Know Me, Respond To Me: Benchmarking Llms For Dynamic User Profiling And Personalized Responses At Scale'
authors: Bowen Jiang, Zhuoqun Hao, Young-min Cho, Bryan Li, Yuan Yuan, Sihao Chen, Lyle Ungar, Camillo J. Taylor, Dan Roth
conference: "Arxiv"
year: 2025
bibkey: jiang2025know
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14225'}
tags: ['RAG', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) have emerged as personalized assistants for
users across a wide range of tasks -- from offering writing support to
delivering tailored recommendations or consultations. Over time, the
interaction history between a user and an LLM can provide extensive information
about an individual's traits and preferences. However, open questions remain on
how well LLMs today can effectively leverage such history to (1) internalize
the user's inherent traits and preferences, (2) track how the user profiling
and preferences evolve over time, and (3) generate personalized responses
accordingly in new scenarios.
  In this work, we introduce the PERSONAMEM benchmark. PERSONAMEM features
curated user profiles with over 180 simulated user-LLM interaction histories,
each containing up to 60 sessions of multi-turn conversations across 15
real-world tasks that require personalization. Given an in-situ user query,
i.e. query issued by the user from the first-person perspective, we evaluate
LLM chatbots' ability to identify the most suitable response according to the
current state of the user's profile. We observe that current LLMs still
struggle to recognize the dynamic evolution in users' profiles over time
through direct prompting approaches. As a consequence, LLMs often fail to
deliver responses that align with users' current situations and preferences,
with frontier models such as GPT-4.1, o4-mini, GPT-4.5, o1, or Gemini-2.0
achieving only around 50% overall accuracy, suggesting room for improvement. We
hope that PERSONAMEM, along with the user profile and conversation simulation
pipeline, can facilitate future research in the development of truly user-aware
chatbots. Code and data are available at github.com/bowen-upenn/PersonaMem.
