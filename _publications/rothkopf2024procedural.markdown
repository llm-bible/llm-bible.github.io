---
layout: publication
title: 'Procedural Adherence And Interpretability Through Neuro-symbolic Generative Agents'
authors: Raven Rothkopf, Hannah Tongxin Zeng, Mark Santolucito
conference: "Arxiv"
year: 2024
bibkey: rothkopf2024procedural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16905"}
tags: ['Interpretability and Explainability', 'Agentic']
---
The surge in popularity of large language models (LLMs) has opened doors for
new approaches to the creation of interactive agents. However, managing and
interpreting the temporal behavior of such agents over the course of a
potentially infinite interaction remain challenging. The stateful, long-term
horizon reasoning required for coherent agent behavior does not fit well into
the LLM paradigm. We propose a combination of formal logic-based program
synthesis and LLM content generation to bring guarantees of procedural
adherence and interpretability to generative agent behavior. To illustrate the
benefit of procedural adherence and interpretability, we use Temporal Stream
Logic (TSL) to generate an automaton that enforces an interpretable, high-level
temporal structure on an agent. With the automaton tracking the context of the
interaction and making decisions to guide the conversation accordingly, we can
drive content generation in a way that allows the LLM to focus on a shorter
context window. We evaluated our approach on different tasks involved in
creating an interactive agent specialized for generating
choose-your-own-adventure games. We found that over all of the tasks, an
automaton-enhanced agent with procedural guarantees achieves at least 96%
adherence to its temporal constraints, whereas a purely LLM-based agent
demonstrates as low as 14.67% adherence.
