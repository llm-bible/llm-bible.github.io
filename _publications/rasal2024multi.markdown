---
layout: publication
title: 'A Multi-llm Orchestration Engine For Personalized, Context-rich Assistance'
authors: Sumedh Rasal
conference: "Arxiv"
year: 2024
bibkey: rasal2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10039'}
tags: ['Reinforcement Learning', 'Applications', 'Model Architecture']
---
In recent years, large language models have demonstrated remarkable
capabilities in natural language understanding and generation. However, these
models often struggle with hallucinations and maintaining long term contextual
relevance, particularly when dealing with private or local data. This paper
presents a novel architecture that addresses these challenges by integrating an
orchestration engine that utilizes multiple LLMs in conjunction with a temporal
graph database and a vector database. The proposed system captures user
interactions, builds a graph representation of conversations, and stores nodes
and edges that map associations between key concepts, entities, and behaviors
over time. This graph based structure allows the system to develop an evolving
understanding of the user preferences, providing personalized and contextually
relevant answers. In addition to this, a vector database encodes private data
to supply detailed information when needed, allowing the LLM to access and
synthesize complex responses. To further enhance reliability, the orchestration
engine coordinates multiple LLMs to generate comprehensive answers and
iteratively reflect on their accuracy. The result is an adaptive, privacy
centric AI assistant capable of offering deeper, more relevant interactions
while minimizing the risk of hallucinations. This paper outlines the
architecture, methodology, and potential applications of this system,
contributing a new direction in personalized, context aware AI assistance.
