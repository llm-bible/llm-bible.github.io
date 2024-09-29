---
layout: publication
title: Procedural Adherence And Interpretability Through Neuro45;symbolic Generative Agents
authors: Rothkopf Raven, Zeng Hannah Tongxin, Santolucito Mark
conference: "Arxiv"
year: 2024
bibkey: rothkopf2024procedural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16905"}
tags: ['Agentic', 'Applications', 'Interpretability And Explainability']
---
The surge in popularity of large language models (LLMs) has opened doors for new approaches to the creation of interactive agents. However managing and interpreting the temporal behavior of such agents over the course of a potentially infinite interaction remain challenging. The stateful long45;term horizon reasoning required for coherent agent behavior does not fit well into the LLM paradigm. We propose a combination of formal logic45;based program synthesis and LLM content generation to bring guarantees of procedural adherence and interpretability to generative agent behavior. To illustrate the benefit of procedural adherence and interpretability we use Temporal Stream Logic (TSL) to generate an automaton that enforces an interpretable high45;level temporal structure on an agent. With the automaton tracking the context of the interaction and making decisions to guide the conversation accordingly we can drive content generation in a way that allows the LLM to focus on a shorter context window. We evaluated our approach on different tasks involved in creating an interactive agent specialized for generating choose45;your45;own45;adventure games. We found that over all of the tasks an automaton45;enhanced agent with procedural guarantees achieves at least 9637; adherence to its temporal constraints whereas a purely LLM45;based agent demonstrates as low as 14.6737; adherence.
