---
layout: publication
title: 'Dialogue-based Generation Of Self-driving Simulation Scenarios Using Large Language Models'
authors: Antonio Valerio Miceli-barone, Alex Lascarides, Craig Innes
conference: "Arxiv"
year: 2023
bibkey: micelibarone2023dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17372"}
tags: ['Multimodal Models', 'Tools', 'Reinforcement Learning']
---
Simulation is an invaluable tool for developing and evaluating controllers
for self-driving cars. Current simulation frameworks are driven by
highly-specialist domain specific languages, and so a natural language
interface would greatly enhance usability. But there is often a gap, consisting
of tacit assumptions the user is making, between a concise English utterance
and the executable code that captures the user's intent. In this paper we
describe a system that addresses this issue by supporting an extended
multimodal interaction: the user can follow up prior instructions with
refinements or revisions, in reaction to the simulations that have been
generated from their utterances so far. We use Large Language Models (LLMs) to
map the user's English utterances in this interaction into domain-specific
code, and so we explore the extent to which LLMs capture the context
sensitivity that's necessary for computing the speaker's intended message in
discourse.
