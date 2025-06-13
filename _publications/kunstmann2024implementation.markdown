---
layout: publication
title: 'Eventchat: Implementation And User-centric Evaluation Of A Large Language Model-driven Conversational Recommender System For Exploring Leisure Events In An SME Context'
authors: Hannes Kunstmann, Joseph Ollier, Joel Persson, Florian Von Wangenheim
conference: "Arxiv"
year: 2024
bibkey: kunstmann2024implementation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.04472'}
tags: ['RAG', 'GPT', 'Tools', 'Model Architecture', 'Prompting', 'RecSys', 'Reinforcement Learning']
---
Large language models (LLMs) present an enormous evolution in the strategic
potential of conversational recommender systems (CRS). Yet to date, research
has predominantly focused upon technical frameworks to implement LLM-driven
CRS, rather than end-user evaluations or strategic implications for firms,
particularly from the perspective of a small to medium enterprises (SME) that
makeup the bedrock of the global economy. In the current paper, we detail the
design of an LLM-driven CRS in an SME setting, and its subsequent performance
in the field using both objective system metrics and subjective user
evaluations. While doing so, we additionally outline a short-form revised
ResQue model for evaluating LLM-driven CRS, enabling replicability in a rapidly
evolving field. Our results reveal good system performance from a user
experience perspective (85.5% recommendation accuracy) but underscore latency,
cost, and quality issues challenging business viability. Notably, with a median
cost of $0.04 per interaction and a latency of 5.7s, cost-effectiveness and
response time emerge as crucial areas for achieving a more user-friendly and
economically viable LLM-driven CRS for SME settings. One major driver of these
costs is the use of an advanced LLM as a ranker within the retrieval-augmented
generation (RAG) technique. Our results additionally indicate that relying
solely on approaches such as Prompt-based learning with ChatGPT as the
underlying LLM makes it challenging to achieve satisfying quality in a
production environment. Strategic considerations for SMEs deploying an
LLM-driven CRS are outlined, particularly considering trade-offs in the current
technical landscape.
