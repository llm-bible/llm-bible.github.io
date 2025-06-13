---
layout: publication
title: 'Open-domain Conversational Search Assistant With Transformers'
authors: Rafael Ferreira, Mariana Leite, David Semedo, Joao Magalhaes
conference: "Arxiv"
year: 2021
bibkey: ferreira2021open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2101.08197'}
tags: ['Agentic', 'Transformer', 'RAG', 'Model Architecture', 'Pretraining Methods']
---
Open-domain conversational search assistants aim at answering user questions
about open topics in a conversational manner. In this paper we show how the
Transformer architecture achieves state-of-the-art results in key IR tasks,
leveraging the creation of conversational assistants that engage in open-domain
conversational search with single, yet informative, answers. In particular, we
propose an open-domain abstractive conversational search agent pipeline to
address two major challenges: first, conversation context-aware search and
second, abstractive search-answers generation. To address the first challenge,
the conversation context is modeled with a query rewriting method that unfolds
the context of the conversation up to a specific moment to search for the
correct answers. These answers are then passed to a Transformer-based re-ranker
to further improve retrieval performance. The second challenge, is tackled with
recent Abstractive Transformer architectures to generate a digest of the top
most relevant passages. Experiments show that Transformers deliver a solid
performance across all tasks in conversational search, outperforming the best
TREC CAsT 2019 baseline.
