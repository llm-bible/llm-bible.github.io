---
layout: publication
title: 'Grillbot In Practice: Lessons And Tradeoffs Deploying Large Language Models For Adaptable Conversational Task Assistants'
authors: Fischer Sophie, Gemmell Carlos, Tecklenburg Niklas, Mackie Iain, Rossetto Federico, Dalton Jeffrey
conference: "Arxiv"
year: 2024
bibkey: fischer2024grillbot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07647"}
tags: ['Applications', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Tools']
---
We tackle the challenge of building real-world multimodal assistants for
complex real-world tasks. We describe the practicalities and challenges of
developing and deploying GRILLBot, a leading (first and second prize winning in
2022 and 2023) system deployed in the Alexa Prize TaskBot Challenge. Building
on our Open Assistant Toolkit (OAT) framework, we propose a hybrid architecture
that leverages Large Language Models (LLMs) and specialised models tuned for
specific subtasks requiring very low latency. OAT allows us to define when, how
and which LLMs should be used in a structured and deployable manner. For
knowledge-grounded question answering and live task adaptations, we show that
LLM reasoning abilities over task context and world knowledge outweigh latency
concerns. For dialogue state management, we implement a code generation
approach and show that specialised smaller models have 84% effectiveness with
100x lower latency. Overall, we provide insights and discuss tradeoffs for
deploying both traditional models and LLMs to users in complex real-world
multimodal environments in the Alexa TaskBot challenge. These experiences will
continue to evolve as LLMs become more capable and efficient -- fundamentally
reshaping OAT and future assistant architectures.
