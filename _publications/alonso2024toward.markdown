---
layout: publication
title: 'Toward Conversational Agents With Context And Time Sensitive Long-term Memory'
authors: Nick Alonso, Tomás Figliolia, Anthony Ndirango, Beren Millidge
conference: "Arxiv"
year: 2024
bibkey: alonso2024toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00057"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
There has recently been growing interest in conversational agents with
long-term memory which has led to the rapid development of language models that
use retrieval-augmented generation (RAG). Until recently, most work on RAG has
focused on information retrieval from large databases of texts, like Wikipedia,
rather than information from long-form conversations. In this paper, we argue
that effective retrieval from long-form conversational data faces two unique
problems compared to static database retrieval: 1) time/event-based queries,
which requires the model to retrieve information about previous conversations
based on time or the order of a conversational event (e.g., the third
conversation on Tuesday), and 2) ambiguous queries that require surrounding
conversational context to understand. To better develop RAG-based agents that
can deal with these challenges, we generate a new dataset of ambiguous and
time-based questions that build upon a recent dataset of long-form, simulated
conversations, and demonstrate that standard RAG based approaches handle such
questions poorly. We then develop a novel retrieval model which combines
chained-of-table search methods, standard vector-database retrieval, and a
prompting method to disambiguate queries, and demonstrate that this approach
substantially improves over current methods at solving these tasks. We believe
that this new dataset and more advanced RAG agent can act as a key benchmark
and stepping stone towards effective memory augmented conversational agents
that can be used in a wide variety of AI applications.
