---
layout: publication
title: 'Plan-grounded Large Language Models For Dual Goal Conversational Settings'
authors: Diogo Glória-silva, Rafael Ferreira, Diogo Tavares, David Semedo, João Magalhães
conference: "Arxiv"
year: 2024
bibkey: glóriasilva2024plan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01053"}
tags: ['Responsible AI', 'Training Techniques']
---
Training Large Language Models (LLMs) to follow user instructions has been
shown to supply the LLM with ample capacity to converse fluently while being
aligned with humans. Yet, it is not completely clear how an LLM can lead a
plan-grounded conversation in mixed-initiative settings where instructions flow
in both directions of the conversation, i.e. both the LLM and the user provide
instructions to one another. In this paper, we tackle a dual goal
mixed-initiative conversational setting where the LLM not only grounds the
conversation on an arbitrary plan but also seeks to satisfy both a procedural
plan and user instructions. The LLM is then responsible for guiding the user
through the plan and, at the same time, adapting to new circumstances,
answering questions, and activating safety guardrails when needed. We propose a
novel LLM that grounds the dialogue on a procedural plan, can take the dialogue
initiative, and enforces guardrails on the system's behavior, while also
improving the LLM's responses to unexpected user behavior. Experiments in
controlled settings and with real users show that the best-performing model,
which we call PlanLLM, achieves a 2.1x improvement over a strong baseline.
Moreover, experiments also show good generalization to unseen domains.
