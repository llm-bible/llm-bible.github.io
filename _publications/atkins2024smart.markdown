---
layout: publication
title: 'Convocache: Smart Re-use Of Chatbot Responses'
authors: Conor Atkins, Ian Wood, Mohamed Ali Kaafar, Hassan Asghar, Nardine Basta, Michal Kepkowski
conference: "Proceedings of Interspeech 2024"
year: 2024
bibkey: atkins2024smart
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18133"}
tags: ['RAG', 'Prompting']
---
We present ConvoCache, a conversational caching system that solves the
problem of slow and expensive generative AI models in spoken chatbots.
ConvoCache finds a semantically similar prompt in the past and reuses the
response. In this paper we evaluate ConvoCache on the DailyDialog dataset. We
find that ConvoCache can apply a UniEval coherence threshold of 90% and respond
to 89% of prompts using the cache with an average latency of 214ms, replacing
LLM and voice synthesis that can take over 1s. To further reduce latency we
test prefetching and find limited usefulness. Prefetching with 80% of a request
leads to a 63% hit rate, and a drop in overall coherence. ConvoCache can be
used with any chatbot to reduce costs by reducing usage of generative AI by up
to 89%.
