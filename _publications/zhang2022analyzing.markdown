---
layout: publication
title: 'Analyzing And Simulating User Utterance Reformulation In Conversational Recommender Systems'
authors: Zhang Shuo, Wang Mu-chun, Balog Krisztian
conference: "Arxiv"
year: 2022
bibkey: zhang2022analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.01763"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
User simulation has been a cost-effective technique for evaluating
conversational recommender systems. However, building a human-like simulator is
still an open challenge. In this work, we focus on how users reformulate their
utterances when a conversational agent fails to understand them. First, we
perform a user study, involving five conversational agents across different
domains, to identify common reformulation types and their transition
relationships. A common pattern that emerges is that persistent users would
first try to rephrase, then simplify, before giving up. Next, to incorporate
the observed reformulation behavior in a user simulator, we introduce the task
of reformulation sequence generation: to generate a sequence of reformulated
utterances with a given intent (rephrase or simplify). We develop methods by
extending transformer models guided by the reformulation type and perform
further filtering based on estimated reading difficulty. We demonstrate the
effectiveness of our approach using both automatic and human evaluation.
