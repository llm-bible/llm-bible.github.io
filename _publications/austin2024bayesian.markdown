---
layout: publication
title: 'Bayesian Optimization With Llm-based Acquisition Functions For Natural Language Preference Elicitation'
authors: David Eric Austin, Anton Korikov, Armin Toroghi, Scott Sanner
conference: "Arxiv"
year: 2024
bibkey: austin2024bayesian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00981"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning']
---
Designing preference elicitation (PE) methodologies that can quickly
ascertain a user's top item preferences in a cold-start setting is a key
challenge for building effective and personalized conversational recommendation
(ConvRec) systems. While large language models (LLMs) enable fully natural
language (NL) PE dialogues, we hypothesize that monolithic LLM NL-PE approaches
lack the multi-turn, decision-theoretic reasoning required to effectively
balance the exploration and exploitation of user preferences towards an
arbitrary item set. In contrast, traditional Bayesian optimization PE methods
define theoretically optimal PE strategies, but cannot generate arbitrary NL
queries or reason over content in NL item descriptions -- requiring users to
express preferences via ratings or comparisons of unfamiliar items. To overcome
the limitations of both approaches, we formulate NL-PE in a Bayesian
Optimization (BO) framework that seeks to actively elicit NL feedback to
identify the best recommendation. Key challenges in generalizing BO to deal
with natural language feedback include determining: (a) how to leverage LLMs to
model the likelihood of NL preference feedback as a function of item utilities,
and (b) how to design an acquisition function for NL BO that can elicit
preferences in the infinite space of language. We demonstrate our framework in
a novel NL-PE algorithm, PEBOL, which uses: 1) Natural Language Inference (NLI)
between user preference utterances and NL item descriptions to maintain
Bayesian preference beliefs, and 2) BO strategies such as Thompson Sampling
(TS) and Upper Confidence Bound (UCB) to steer LLM query generation. We
numerically evaluate our methods in controlled simulations, finding that after
10 turns of dialogue, PEBOL can achieve an MRR@10 of up to 0.27 compared to the
best monolithic LLM baseline's MRR@10 of 0.17, despite relying on earlier and
smaller LLMs.
