---
layout: publication
title: 'Automated Test Generation To Evaluate Tool-augmented Llms As Conversational AI Agents'
authors: Samuel Arcadinho, David Aparicio, Mariana Almeida
conference: "Arxiv"
year: 2024
bibkey: arcadinho2024automated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15934'}
tags: ['Reinforcement Learning', 'Agentic', 'RAG', 'Tools']
---
Tool-augmented LLMs are a promising approach to create AI agents that can
have realistic conversations, follow procedures, and call appropriate
functions. However, evaluating them is challenging due to the diversity of
possible conversations, and existing datasets focus only on single interactions
and function-calling. We present a test generation pipeline to evaluate LLMs as
conversational AI agents. Our framework uses LLMs to generate diverse tests
grounded on user-defined procedures. For that, we use intermediate graphs to
limit the LLM test generator's tendency to hallucinate content that is not
grounded on input procedures, and enforces high coverage of the possible
conversations. Additionally, we put forward ALMITA, a manually curated dataset
for evaluating AI agents in customer support, and use it to evaluate existing
LLMs. Our results show that while tool-augmented LLMs perform well in single
interactions, they often struggle to handle complete conversations. While our
focus is on customer support, our method is general and capable of AI agents
for different domains.
