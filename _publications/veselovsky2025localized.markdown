---
layout: publication
title: 'Localized Cultural Knowledge Is Conserved And Controllable In Large Language Models'
authors: Veniamin Veselovsky, Berke Argin, Benedikt Stroebl, Chris Wendler, Robert West, James Evans, Thomas L. Griffiths, Arvind Narayanan
conference: "Arxiv"
year: 2025
bibkey: veselovsky2025localized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10191"}
tags: ['Prompting', 'Reinforcement Learning']
---
Just as humans display language patterns influenced by their native tongue
when speaking new languages, LLMs often default to English-centric responses
even when generating in other languages. Nevertheless, we observe that local
cultural information persists within the models and can be readily activated
for cultural customization. We first demonstrate that explicitly providing
cultural context in prompts significantly improves the models' ability to
generate culturally localized responses. We term the disparity in model
performance with versus without explicit cultural context the explicit-implicit
localization gap, indicating that while cultural knowledge exists within LLMs,
it may not naturally surface in multilingual interactions if cultural context
is not explicitly provided. Despite the explicit prompting benefit, however,
the answers reduce in diversity and tend toward stereotypes. Second, we
identify an explicit cultural customization vector, conserved across all
non-English languages we explore, which enables LLMs to be steered from the
synthetic English cultural world-model toward each non-English cultural world.
Steered responses retain the diversity of implicit prompting and reduce
stereotypes to dramatically improve the potential for customization. We discuss
the implications of explicit cultural customization for understanding the
conservation of alternative cultural world models within LLMs, and their
controllable utility for translation, cultural customization, and the
possibility of making the explicit implicit through soft control for expanded
LLM function and appeal.
