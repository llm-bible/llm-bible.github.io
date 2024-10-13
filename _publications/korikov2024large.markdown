---
layout: publication
title: 'Large Language Model Driven Recommendation'
authors: Korikov Anton, Sanner Scott, Deldjoo Yashar, He Zhankui, Mcauley Julian, Ramisa Arnau, Vidal Rene, Sathiamoorthy Mahesh, Kasrizadeh Atoosa, Milano Silvia, Ricci Francesco
conference: "Arxiv"
year: 2024
bibkey: korikov2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10946"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
While previous chapters focused on recommendation systems (RSs) based on
standardized, non-verbal user feedback such as purchases, views, and clicks --
the advent of LLMs has unlocked the use of natural language (NL) interactions
for recommendation. This chapter discusses how LLMs' abilities for general NL
reasoning present novel opportunities to build highly personalized RSs -- which
can effectively connect nuanced and diverse user preferences to items,
potentially via interactive dialogues. To begin this discussion, we first
present a taxonomy of the key data sources for language-driven recommendation,
covering item descriptions, user-system interactions, and user profiles. We
then proceed to fundamental techniques for LLM recommendation, reviewing the
use of encoder-only and autoregressive LLM recommendation in both tuned and
untuned settings. Afterwards, we move to multi-module recommendation
architectures in which LLMs interact with components such as retrievers and RSs
in multi-stage pipelines. This brings us to architectures for conversational
recommender systems (CRSs), in which LLMs facilitate multi-turn dialogues where
each turn presents an opportunity not only to make recommendations, but also to
engage with the user in interactive preference elicitation, critiquing, and
question-answering.
