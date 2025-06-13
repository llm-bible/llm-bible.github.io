---
layout: publication
title: 'Eliciting Problem Specifications Via Large Language Models'
authors: Robert E. Wray, James R. Kirk, John E. Laird
conference: "Arxiv"
year: 2024
bibkey: wray2024eliciting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.12147'}
tags: ['Prompting', 'Agentic']
---
Cognitive systems generally require a human to translate a problem definition
into some specification that the cognitive system can use to attempt to solve
the problem or perform the task. In this paper, we illustrate that large
language models (LLMs) can be utilized to map a problem class, defined in
natural language, into a semi-formal specification that can then be utilized by
an existing reasoning and learning system to solve instances from the problem
class. We present the design of LLM-enabled cognitive task analyst agent(s).
Implemented with LLM agents, this system produces a definition of problem
spaces for tasks specified in natural language. LLM prompts are derived from
the definition of problem spaces in the AI literature and general
problem-solving strategies (Polya's How to Solve It). A cognitive system can
then use the problem-space specification, applying domain-general problem
solving strategies ("weak methods" such as search), to solve multiple instances
of problems from the problem class. This result, while preliminary, suggests
the potential for speeding cognitive systems research via disintermediation of
problem formulation while also retaining core capabilities of cognitive
systems, such as robust inference and online learning.
