---
layout: publication
title: 'Open-source Large Language Models As Multilingual Crowdworkers: Synthesizing Open-domain Dialogues In Several Languages With No Examples In Targets And No Machine Translation'
authors: Ahmed Njifenjou, Virgile Sucal, Bassam Jabaian, Fabrice Lefèvre
conference: "Arxiv"
year: 2025
bibkey: njifenjou2025open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03462"}
tags: ['Fine-Tuning', 'Agentic', 'Applications', 'RAG', 'Reinforcement Learning']
---
The prevailing paradigm in the domain of Open-Domain Dialogue agents
predominantly focuses on the English language, encompassing both models and
datasets. Furthermore, the financial and temporal investments required for
crowdsourcing such datasets for finetuning are substantial, particularly when
multiple languages are involved. Fortunately, advancements in Large Language
Models (LLMs) have unveiled a plethora of possibilities across diverse tasks.
Specifically, instruction-tuning has enabled LLMs to execute tasks based on
natural language instructions, occasionally surpassing the performance of human
crowdworkers. Additionally, these models possess the capability to function in
various languages within a single thread. Consequently, to generate new samples
in different languages, we propose leveraging these capabilities to replicate
the data collection process. We introduce a pipeline for generating Open-Domain
Dialogue data in multiple Target Languages using LLMs, with demonstrations
provided in a unique Source Language. By eschewing explicit Machine Translation
in this approach, we enhance the adherence to language-specific nuances. We
apply this methodology to the PersonaChat dataset. To enhance the openness of
generated dialogues and mimic real life scenarii, we added the notion of speech
events corresponding to the type of conversation the speakers are involved in
and also that of common ground which represents the premises of a conversation.
